# shared-calendar
Shared Calendar with Friends and Family
# Easyvite

**Easyvite** is a lightweight scheduling assistant that helps groups of friends (or couples) quickly find a time and lock plans — without endless group texts.

This repo contains a **no-backend demo MVP** that runs entirely on GitHub Pages and works in any modern browser.

---

## 🚀 What This Demo Does

This version is intentionally simple and fast to try.

### Current features (working today)
- Create an event (e.g. Dinner, Workout, Trip Planning)
- Automatically propose 3 time options
- Share a link with friends
- Collect availability votes:
  - ✅ Yes
  - ⚠️ Maybe
  - ❌ No
- Organizer locks a time
- Generate an **Add to Calendar (.ics)** file that works with:
  - Apple Calendar
  - Google Calendar
  - Outlook

No accounts. No downloads. No calendar permissions required.

---

## 🧪 How the Demo Works

- The landing page lives at `index.html`
- The interactive demo lives at `demo.html`
- All data is stored locally in the browser using `localStorage`
- There is **no backend** in this version

This makes it extremely easy to host and test, but comes with one limitation (see below).

---

## ⚠️ Important Demo Limitation

Because this demo has **no backend**:

- Events are saved **only on the device/browser that created them**
- Invite links work best when tested on the **same device**
- Opening the invite link on another phone may show “Event not found”

👉 This is expected behavior and will be solved in the next phase by adding a backend (Firebase).

---

## 🌍 Make It Live (GitHub Pages)

You can host this demo publicly in under 5 minutes.

### Steps
1. Create a new GitHub repository (e.g. `easyvite`)
2. Upload these files to the repo root:
   - `index.html`
   - `demo.html`
3. Go to **Settings → Pages**
4. Set:
   - **Source:** Deploy from a branch  
   - **Branch:** `main`  
   - **Folder:** `/ (root)`
5. Your site will be live at:


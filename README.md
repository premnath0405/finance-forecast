# Finance Forecast — PWA

A self-saving personal finance tracker that works offline and installs on any device.

## What you get
- Opens as an app on iPhone, Android, and desktop (no App Store needed)
- Works fully offline
- Auto-saves everything to your device as you type — nothing is lost on close
- Optionally links to a Drive Excel for backup and cross-device sync

---

## Deploy to GitHub Pages in 5 steps

### 1. Create a GitHub account (if you don't have one)
Go to [github.com](https://github.com) → Sign up (free).

### 2. Create a new repository
- Click the **+** button → **New repository**
- Name it `finance-forecast` (or anything you like)
- Set it to **Public** (required for free GitHub Pages)
- Click **Create repository**

### 3. Upload these files
In your new repo, click **uploading an existing file** (or **Add file → Upload files**).

Upload all five files in this folder:
- `index.html`
- `manifest.json`
- `sw.js`
- `icon-192.png`
- `icon-512.png`

Click **Commit changes**.

### 4. Enable GitHub Pages
- Go to your repo → **Settings** → **Pages** (left sidebar)
- Under **Source**, select **Deploy from a branch**
- Branch: **main**, folder: **/ (root)**
- Click **Save**

Wait about 60 seconds, then your app is live at:
`https://YOUR-GITHUB-USERNAME.github.io/finance-forecast/`

### 5. Install the app
**On iPhone (Safari):**
1. Open the URL above in Safari
2. Tap the **Share** button (box with arrow)
3. Tap **Add to Home Screen**
4. Tap **Add** — it now appears as an app icon

**On Android (Chrome):**
1. Open the URL in Chrome
2. Tap the **three-dot menu** → **Add to Home screen**
3. Tap **Add**

**On desktop (Chrome/Edge):**
1. Open the URL
2. Click the **install icon** in the address bar (looks like a monitor with a down arrow)
3. Click **Install**

---

## Syncing between devices
Each installed instance saves data to its own device storage independently.
To sync: use **Export to Excel** on one device, move the file to the other device (email, Drive, etc.), and **Import file** there. Future auto-saves on that device will update that file.

## Updating the app
If you ever update `index.html`, re-upload it to GitHub. The service worker will pick up the new version next time the user opens the app while online.

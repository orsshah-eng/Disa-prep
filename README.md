# DISA Prep Simulator by CA Onil Shah

Installable study app (DISA + CISA MCQs, mock tests, concept flashcards, study log). Works offline once installed.

## Put it online with GitHub Pages (one time, ~5 minutes)
1. Sign in at github.com → **New repository** → name it `disa-prep` → Public → **Create repository**.
2. On the new repo page click **uploading an existing file** and drag in **everything in this folder**
   (`index.html`, `manifest.webmanifest`, `sw.js`, the `icons` folder and this README) → **Commit changes**.
3. Repo **Settings → Pages** → Source: **Deploy from a branch** → Branch: `main`, folder `/ (root)` → **Save**.
4. After about a minute the link appears: `https://<your-username>.github.io/disa-prep/`

## Install on Android
Open the link in **Chrome** → tap **Install** on the dashboard (or ⋮ menu → **Install app / Add to Home screen**).
The "DISA Prep" icon appears on the home screen; the app opens full-screen and works without internet.

## Progress, log and history
Saved inside the app on each phone (answers, attempt history, daily log, mock tests, flashcards).
Use **Dashboard → Save backup** now and then. To move progress from the old HTML file: Save backup there → Restore backup in the app.

## Updating later
Replace `index.html` in the repo and change `VERSION` in `sw.js` (e.g. `disa-prep-v2`). Phones pick up the update the next time the app is opened online.

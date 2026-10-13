# Excellent Child Academy

A responsive school administration dashboard starter built with plain HTML, CSS and JavaScript. It runs without a frontend build step and is configured for Railway.

## Features
- Dashboard overview and summary cards
- Student records: add, search, and delete
- Teacher records: add and delete
- Attendance register
- Fee tracking
- Results overview
- Responsive layout for phones, tablets, and computers
- Sample records so the app is populated on first open
- Browser local storage to retain changes in the same browser

## Run locally
Requires Node.js 18 or newer.

```bash
npm start
```

Open `http://localhost:3000`.

## Deploy to Railway
1. Upload the **contents** of this ZIP to a GitHub repository (not just the ZIP file itself).
2. In Railway, choose **New Project → Deploy from GitHub Repo**.
3. Select the repository. Railway detects `package.json` and runs `npm start`.
4. Open the generated public domain after deployment finishes.

The included `railway.json` provides the start command. No environment variables are required.

## Important data note
This version stores edits in the current browser using `localStorage`. It is a working front-end prototype, not a multi-user production school database. Records will not automatically sync between devices or users. Before using real student information, add a secure backend/database, staff authentication, backups, and appropriate privacy protections. Do not put real student data into this demo.

## GitHub Pages
This project is designed for Railway or another Node.js host because it includes a small server. For GitHub Pages, the files in `public/` can be published as a static site, but browser data remains local to each visitor.

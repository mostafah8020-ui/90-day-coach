# 90 Day Coach — PWA

This folder is a ready-to-host Progressive Web App.

## What is already included
- Mobile-first coach UI
- Food and drink quick logging
- Workout logging and progression history
- Daily check-ins
- Supplements page
- Complete timeline/history
- Local data persistence
- JSON export/import
- PWA manifest
- Offline service worker
- Home-screen install support when served over HTTPS

## Important
The current app stores its live data locally in the browser. The PWA packaging does not automatically create cloud sync or an account database.

To get a permanent HTTPS URL and install it from Chrome, publish this folder on a static HTTPS host such as GitHub Pages, Cloudflare Pages, or Netlify.

For true multi-device history, the next engineering step is a backend/database + authentication layer. That requires choosing a hosting/database account and authorizing access.

# Electrical Cable Selector V6 — LV & MV up to 22 kV

Static single-page web app prepared for GitHub Pages / PWA installation.

## Files
- `index.html` — main application
- `manifest.json` — PWA manifest
- `sw.js` — offline cache/service worker
- `icon-192.png`, `icon-512.png` — app icons

## Deploy with GitHub Pages
1. Create a new GitHub repository.
2. Upload all files in this folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then Save.
6. Open the GitHub Pages URL after deployment.

### Update note
When publishing a future version, change `CACHE_NAME` in `sw.js` (for example from `...-1` to `...-2`) so devices refresh cached files cleanly.

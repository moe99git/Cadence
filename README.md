# Cadence (PWA)

Generative focus / relax / sleep / meditate music, synthesized in the browser with Web Audio.

## Deploy on GitHub Pages
1. Create a new GitHub repo (e.g. `cadence`) and upload every file in this folder to the repo root.
2. Repo → Settings → Pages → "Deploy from a branch" → branch `main`, folder `/ (root)` → Save.
3. After a minute, open `https://<your-username>.github.io/<repo>/` on your phone.
4. Android Chrome: menu → Install app. iOS Safari: Share → Add to Home Screen.

All paths are relative, so it works under the `/<repo>/` subpath. To update, change `CACHE` in `sw.js` (e.g. `cadence-v2`).

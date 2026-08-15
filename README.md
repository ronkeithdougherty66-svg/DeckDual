# Deck Duel

A single-player card duel (based on the classic game of War) — draw cards, battle for the pot, and fight for the whole deck. Built as a single self-contained web page, playable offline once loaded, with a custom purple app icon for Android.

## 1. Put this on GitHub

1. Create a new repository on GitHub (e.g. `deck-duel`).
2. Upload all the files in this folder, keeping the structure:
   ```
   index.html
   manifest.json
   assets/
     icon-192.png
     icon-512.png
     icon-maskable-512.png
     apple-touch-icon.png
     favicon-32.png
   ```
   Easiest way: on the repo's GitHub page, click **Add file → Upload files**, drag in everything (including the `assets` folder), and commit.

## 2. Turn on GitHub Pages

1. In the repo, go to **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
3. Set **Branch** to `main` (or `master`) and folder to `/ (root)`, then **Save**.
4. Wait a minute, then refresh — GitHub will show a URL like:
   `https://<your-username>.github.io/deck-duel/`

That URL is the link to send your wife.

## 3. Install it on her phone (Android)

1. Open the GitHub Pages link above in **Chrome** on her phone.
2. Tap the **⋮** menu → **Add to Home screen** → **Add**.
3. The purple Deck Duel icon appears on her home screen and launches full-screen, like a real app — no browser bar, works offline after the first load.

## Notes

- No backend, accounts, or install from an app store needed — it's just a webpage that behaves like an app once added to the home screen.
- To make future edits (colors, rules, names), just update `index.html` in the repo and push — GitHub Pages redeploys automatically within a minute or two.
- The icon files live in `assets/` and are referenced by `manifest.json` (used by Android's "Add to Home screen") and by `apple-touch-icon.png` (used by iOS, if she ever plays on an iPhone instead).

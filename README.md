# Planets 🪐

A playful pinch-zoom solar system explorer for kids, built as a web app.

## Play it locally
Just open `Solar System.html` in any modern browser.

## Put it on your iPad (free, via GitHub Pages)

1. **Create a GitHub repo** (public) — name it anything, e.g. `planets`.
2. **Upload these files** to the repo root:
   - `Solar System.html`
   - `index.html`
   - `manifest.webmanifest`
   - `icon.svg`
3. **Enable GitHub Pages:**
   - Repo **Settings** → **Pages**
   - Under **Build and deployment**, set **Source** → **Deploy from a branch**
   - Branch: `main`, folder: `/ (root)` → **Save**
   - Wait ~30 seconds. Pages will show a URL like `https://<you>.github.io/planets/`
4. **On the iPad**, open that URL in **Safari**.
5. Tap the **Share** button (square with an up arrow) → **Add to Home Screen** → **Add**.
6. Tap the new icon on the home screen — it launches fullscreen like a real app.

## Generating PNG icons (optional, for better Android support)
iOS accepts the SVG icon fine. If you want 192/512 PNG versions for Android/PWA stores, export `icon.svg` from any image editor (or https://realfavicongenerator.net) and drop `icon-192.png` + `icon-512.png` next to `icon.svg`.

## Controls
- **Pinch** to zoom
- **Drag** to pan
- **Double-tap** to zoom in/out fast
- **Tap Earth** to toggle night side (city lights ✨)
- **↺ Reset** to return home

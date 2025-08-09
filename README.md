
# Numberblock 80 — Swipe Gallery

A single-page, swipe‑through gallery where each picture fills the screen and you swipe **top → bottom** to go through them. Built with vanilla HTML/CSS/JS and **CSS scroll‑snap** (super smooth on mobile). No frameworks, no build step.

## Quick start
1. Unzip this folder.
2. Put your images (or short videos) into the `images/` folder.
3. **Option A (easiest):** Edit `images.json` and list your files (e.g., `"images/my-photo.jpg"`).
4. **Option B:** Open `index.html` and add direct URLs in the `IMAGE_SOURCES` array.
5. Open `index.html` in a browser. Swipe/scroll from top to bottom. Tap **Thumbnails** for a bottom strip.

### Bonus: Local-only mode
You can also click **Load photos** or drag & drop files straight into the page to view images **without uploading** anything (great for phones).

### Bonus: URL parameter
Pass a comma- or newline-separated list of image URLs in the address bar:
```
index.html?urls=https://example.com/one.jpg,https://example.com/two.jpg
```

## Deploy (GitHub Pages)
1. Create a new GitHub repo (e.g., `numberblock-80-gallery`).
2. Upload `index.html`, `images.json`, and your `images/` folder.
3. Enable GitHub Pages (Settings → Pages → Deploy from branch).
4. Visit your GitHub Pages URL.

## Keyboard shortcuts
- **Arrow Down / Space / PageDown**: next slide
- **Arrow Up / PageUp**: previous slide
- **T**: toggle thumbnails

## Notes
- Images are lazy-loaded for speed.
- Videos (mp4/webm/mov) are supported; they show controls and play inline.
- On iOS/Android, the experience feels like swiping between full-screen panels.

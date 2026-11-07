# Squish

A 3D cell-division toy for phones: press and hold a cell until it divides, small paper creatures pop out, clumped cells fuse into big ones, and the brood breeds, fights, trades and dies, leaving map pieces pasted into the grid.

## Files
- `index.html` — the whole app (Three.js r128 loads from cdnjs; Caveat font from Google Fonts)
- `maps.jpg` — the map-paper atlas (fragments of 20 public-domain maps from Wikimedia Commons)

## Deploy to Vercel
Option A — drag and drop: go to vercel.com/new, choose "Deploy" from a folder/upload, and drop this folder.
Option B — CLI: `npm i -g vercel`, then run `vercel` in this folder (no build step; framework preset "Other").

Test locally with any static server, e.g. `npx serve .` (opening index.html directly from disk won't load maps.jpg in some browsers).

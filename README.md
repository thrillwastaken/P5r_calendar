# P5R Daily Guide — PWA

A Persona 5 Royal 100% daily walkthrough companion app, based on Hurricanehaon's guide.

## How to install on Android

### Option A: GitHub Pages (free hosting, easiest)

1. Create a free account at github.com
2. Create a new repository (e.g. `p5r-guide`)
3. Upload ALL files in this folder:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icons/` folder (all 8 PNGs)
4. Go to repository Settings → Pages → Source: Deploy from branch → main → / (root)
5. Wait ~1 minute, then visit `https://YOUR-USERNAME.github.io/p5r-guide`
6. On your Android phone, open that URL in Chrome
7. Tap the three-dot menu → "Add to Home screen"
8. The app installs with an icon and works fully offline!

### Option B: Netlify (drag and drop, even easier)

1. Go to netlify.com → sign up free
2. Drag the ENTIRE folder onto the Netlify dashboard
3. It gives you a URL like `https://random-name.netlify.app`
4. Open on Android in Chrome → Add to Home screen

### Option C: Locally on your phone (no hosting)

1. Copy `index.html` to your phone
2. Open it with Chrome (File manager → tap file → open with Chrome)
3. Works but without offline/install features

## File structure

```
p5r-guide/
├── index.html       ← The full app (279 days of guide content)
├── manifest.json    ← Makes it installable as an app
├── sw.js            ← Service worker for offline support
└── icons/
    ├── icon-72x72.png
    ├── icon-96x96.png
    ├── icon-128x128.png
    ├── icon-144x144.png
    ├── icon-152x152.png
    ├── icon-192x192.png
    ├── icon-384x384.png
    └── icon-512x512.png
```

## Features
- 279 days from April 9th through March
- Day-by-day steps from Hurricanehaon's 100% guide
- 💾 Save Abuse warnings highlighted in orange
- Checkboxes per step, progress saves locally
- Works fully offline once installed
- Calendar + Overview + Day detail views

# RPS Dharuhera, interactive 3D campus site

Static site (HTML, CSS, JavaScript, Three.js via CDN). No build step, backend or API keys.

## Deploy on GitHub Pages
1. Create a repository and upload the contents of this folder so `index.html` is at the repo root.
2. Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
3. Open `https://<username>.github.io/<repo>/` after about a minute.

You can also open `index.html` locally. An internet connection is needed for Three.js and fonts; without it the page shows a static fallback.

## Structure
`js/data.js` zones and tour copy · `scene.js` renderer, camera, day/night, quality · `campus.js` procedural campus · `interaction.js` picking, panel, controls · `tour.js` guided tour · `navigation.js` nav · `main.js` boot and fallback.

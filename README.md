# Wheel of Rest

## Structure
- `index.html` markup
- `css/styles.css` presentation
- `js/app.js` startup and data loading
- `js/wheel.js` SVG rendering and interaction
- `js/ui.js` menus and controls
- `js/csv.js` CSV parser
- `data/wheel-of-rest.csv` editable data

## Run locally
Because ES modules and `fetch()` are used, serve the folder rather than opening `index.html` directly. Example: `python -m http.server 8000`, then open `http://localhost:8000/wheel-of-rest-web/`.

For online hosting, upload the folder contents to any static web host.

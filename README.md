# Centroid Visualiser

An interactive, single-file HTML demo that teaches the **centroid** of a set of points — the arithmetic mean of their coordinates.

![HTML5](https://img.shields.io/badge/HTML5-Canvas-orange) ![No Dependencies](https://img.shields.io/badge/dependencies-none-brightgreen) ![License](https://img.shields.io/badge/license-MIT-blue)

## What is a Centroid?

The centroid of *n* points is their "centre of mass," computed as:

> **c_x = (1/n) Sigma x_i ,  c_y = (1/n) Sigma y_i**

This demo lets you build intuition by placing points on a canvas and watching the centroid shift in real time.

## Demo

1. **Download or clone** this repository.
2. **Open `index.html`** in any modern browser (double-click the file — no server needed).
3. **Click** inside the canvas to add points and observe the centroid.

No build step, no dependencies, no Node.js — just one HTML file.

## Features

| Feature | Description |
|---|---|
| **Add points** | Click anywhere on the canvas to place a blue point |
| **Live centroid** | A red marker with crosshairs updates instantly |
| **Stats panel** | Shows point count and centroid coordinates (1 d.p.) |
| **Undo** | Remove the last point added |
| **Clear** | Reset the canvas |
| **HiDPI support** | Crisp rendering on Retina / high-DPI displays via `devicePixelRatio` scaling |

## Project Structure

```
.
└── index.html   ← entire app (HTML + CSS + JS, ~180 lines)
```

## Browser Support

Works in all modern browsers that support the HTML5 Canvas API:

- Chrome / Edge
- Firefox
- Safari

## License

MIT — use it however you like.

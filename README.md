# GridLess Creative Studio

GridLess is a browser-based collection of creative tools. Open `index.html` to use the app launcher.

## Apps

| Page | Tool | What it does |
|---|---|---|
| `index.html` | Creative Studio | Home page, app search and category filters |
| `builder.html` | AI Website Builder | Original local AI website builder, preserved from the previous homepage |
| `photoshop.html` | GridLess Photo | Open images, draw, add text, adjust brightness/contrast/saturation, export PNG |
| `3deditor.html` | 3D Studio | Build a 3D scene from primitives, orbit the camera, adjust objects, export scene JSON |
| `vector.html` | Vector Lab | Create and move SVG shapes and text, style them, export SVG |
| `audio.html` | Beat Lab | Browser-generated step sequencer with drums and synth tones |
| `video.html` | Video Desk | Preview a local video, set in/out points, adjust preview effects, download the source |
| `pixel.html` | Pixel Studio | Draw pixel art on a grid and export PNG |
| `color.html` | Color Studio | Generate colour harmonies and copy palette values |
| `markdown.html` | Markdown Pad | Write Markdown with a live preview and download notes |

## Running it

- Open `index.html` in a modern browser, or deploy the repository with GitHub Pages.
- The 3D editor loads Three.js from jsDelivr, so it needs an internet connection.
- The AI builder uses WebGPU and downloads its selected model into the browser; a supported browser and enough device memory are required.
- Other creative tools work locally in the browser. Your source files are not uploaded by these pages.

## Notes

This project is a growing set of lightweight browser tools, not a replacement for every feature in professional desktop creative software. The video desk currently provides preview, trim-point controls and source download; it does not render a newly trimmed video file.

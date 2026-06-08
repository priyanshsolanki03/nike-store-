# Nike Store — React + Vite + Tailwind

A small Nike-store UI demo built with React, Vite, and Tailwind CSS. It demonstrates a product listing, cart management (Redux-like slice), responsive layout, and simple UI components.

## Features

- Product listing and details (UI-only sample data)
- Cart state management using `CartSlice.js` / local store
- Responsive components built with Tailwind CSS
- Video / media asset support in `src/assets/video`

## Getting Started

Requirements

- Node.js 16+ (or current LTS)

Install

```bash
npm install
```

Run (development)

```bash
npm run dev
```

Build

```bash
npm run build
```

Preview production build

```bash
npm run preview
```

## Project Structure

- `index.html` — app entry HTML
- `src/` — source files
  - `main.jsx`, `App.jsx` — app bootstrap and root
  - `app/Store.js`, `app/CartSlice.js` — simple store + cart slice
  - `components/` — UI components (Navbar, Footer, Cart, Hero, etc.)
  - `data/data.js` — demo product data
  - `assets/` — images & video

## Notes

- Tailwind configuration is in `tailwind.config.cjs` and PostCSS in `postcss.config.cjs`.
- Vite config: `vite.config.js`.

## Contributing

PRs welcome — open an issue first for larger changes.

## License

This project is provided as-is for learning/demo purposes. Add a license if you plan to publish.

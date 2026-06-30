# Lumen Reader

A local-first annotated PDF reader for research papers. Upload a PDF, let LiteParse WASM extract sections in the browser, then read one section at a time with large focused text and Web Speech playback.

## Run Locally

```sh
npm install
npm run dev
```

## Build

```sh
npm run build
```

The production site is emitted to `dist/`.

## Deploy To GitHub Pages

Push this project to a GitHub repository with a `main` branch, then enable Pages with **Source: GitHub Actions**. The workflow in `.github/workflows/deploy.yml` builds the Vite app and publishes `dist/`.

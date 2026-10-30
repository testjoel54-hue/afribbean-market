# Afribbean Market — Vite / Vercel project

This project retains the original Afribbean Market design, HTML structure, CSS, JavaScript, and embedded image assets. The original `index.html` is unchanged. Vite is used only for local development and a static production build.

## Requirements

- Node.js 22.12 or newer
- npm

## Develop locally

```bash
npm install
npm run dev
```

Open the local URL shown by Vite (usually http://localhost:5173/).

## Build and preview

```bash
npm run build
npm run preview
```

The production output is generated inside `dist/`.

## Deploy to Vercel

1. Upload this project to a Git repository and import it in Vercel, or deploy the project using the Vercel CLI.
2. Framework preset: **Vite**.
3. Install command: **npm install**.
4. Build command: **npm run build**.
5. Output directory: **dist**.
6. Deploy.

`vercel.json` includes the build and output settings. Vercel should automatically detect the Vite project.

## Original website

The original website contains one `index.html` with inline CSS, JavaScript and base64-embedded images. No images or style files were relocated. Google Fonts and external social links still use the URLs from the original.

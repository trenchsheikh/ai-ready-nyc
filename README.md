# AI Ready NYC

Three-day AI literacy programme website for football, creativity, technology and BBC Pathfinder activities.

## Current production source

The deployable app lives in [`ai-ready-nyc-with-artwork/`](./ai-ready-nyc-with-artwork/). This directory contains the Vite entry point, styles, app script and generated visual assets. The historical `index.html` at repository root is not used for deployment.

## Vercel (`darkbet` workspace)

- Project: `ai-ready-nyc`
- Root Directory: `ai-ready-nyc-with-artwork`
- Framework: Vite
- Build Command: `npm run build`
- Output Directory: `dist`
- Production URL: https://ai-ready-nyc.vercel.app

## Local development

```bash
cd ai-ready-nyc-with-artwork
npm install
npm run dev
```

## Local production build

```bash
npm run build
```

The `assets/` directory contains the generated image artwork. Keep the image files alongside their references in `src.js` and `style.css` to avoid broken links.

Note: The programme content and Pathfinder links are a prototype; confirm destinations and partner approvals before public launch.

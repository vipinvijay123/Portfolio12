# Vipin Vijay — Portfolio

Personal portfolio built on the ThreeUI `KageLandingPage` experience (Vite + React + TypeScript, Three.js).

Content is taken from the résumé in `public/vipin-vijay-resume.pdf`.

## Scripts

- `npm run dev` — local development server
- `npm run build` — type-check and production build to `dist/`
- `npm run preview` — serve the production build locally

## Deploy to Vercel

1. Push this folder to a Git repository, or import it directly with the Vercel CLI.
2. Vercel detects Vite from `vercel.json`: install `npm ci`, build `npm run build`, output `dist`.
3. No environment variables are required.

## Structure

- `src/` — React entry point and the `KageLandingPage` configuration
- `public/landing-pages/kage.html` — the authored Kage page, with portfolio copy
- `public/landing-pages/secret-pathways-assets/` — the scene layers, fonts stylesheet and Three.js runtime
- `public/vipin-vijay-resume.pdf` — the résumé served by the Download button

## Notes

- The Kage page loads its display font from the URL in `secret-pathways-assets/fonts.css`, so that host must be reachable at runtime.
- Asset licences are in `node_modules/@designcodeio/threeui/ASSET-LICENSES.md` and `FONT-LICENSES.md`.

# GDSFF Official Website

> ## Superseded — do not deploy from this repository
>
> The live GDSFF site is built and deployed from
> [`regcoffeenyc/gdsff-launch`](https://github.com/regcoffeenyc/gdsff-launch),
> which carries this project's history. Of the 63 files here, 61 also exist there.
> `gdsff-launch/package.json` is still named `gdsff-codex-dropin`, which is the
> shared lineage.
>
> This repository has not changed since 15 March 2026 and is kept for history only.
> The local paths in the Notes section below point at a Windows desktop and no
> longer resolve for anyone.

Official Vite/React website for the Georgian Dynamic Shooting & Functional Fitness Federation (GDSFF).

## Stack

- React
- Vite
- React Router

## Local Development

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Create a production build:

```bash
npm run build
```

Preview the production build locally:

```bash
npm run preview
```

## Deployment

The site is configured for static deployment with Vite and uses hash-based routing, so no custom rewrite rules are required for standard static hosting.

### Vercel

1. Import the repository into Vercel.
2. Set the framework preset to `Vite` if Vercel does not detect it automatically.
3. Use these settings:
   - Build command: `npm run build`
   - Output directory: `dist`
4. Deploy.

### Netlify

1. Create a new site from the repository in Netlify.
2. Use these build settings:
   - Build command: `npm run build`
   - Publish directory: `dist`
3. Deploy the site.

## Notes

- Public assets live in `public`.
- Main application code lives in `src`.
- The site is bilingual and supports English and Georgian content from shared content files.

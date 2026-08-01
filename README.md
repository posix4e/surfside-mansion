# Surfside Mansion

Landing page for **Surfside Mansion**, a family-run artist residency at our home in coastal Puerto Rico. We cover visiting artists' housing, food, transportation, and a stipend — at no cost to the artist — in exchange for under 20 hours a week of playful creative time with our family.

The site is a single self-contained HTML file (`public/index.html`) with all CSS inlined, no external dependencies, and no JavaScript. Photo slots are CSS gradient placeholders labeled "Photo coming soon" so real photos can be swapped in later.

## Develop

```sh
npm install
npm run dev
```

## Deploy

Hosted on Cloudflare Workers (static assets) at [residence.fralex.art](https://residence.fralex.art).

Every push to `main` deploys automatically via GitHub Actions (`.github/workflows/deploy.yml`), using the `CLOUDFLARE_API_TOKEN` repo secret. To deploy manually instead:

```sh
npm run deploy
```

## Contact

info@fralex.art

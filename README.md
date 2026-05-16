# zbdconsulting-site

Source for **zbdconsulting.com** — ZBD Solutions launch page + brief form.

## What this repo is

Static HTML site, deployed via Netlify auto-deploy on push to `main`.

| File | Purpose |
|---|---|
| `index.html` | Main landing page (3 lanes + ROI + contractor verticals + CTA + footer) |
| `brief.html` | Lane 03 form page (Netlify Form `zbds-brief`) |
| `thanks.html` | Post-submit confirmation |
| `404.html` | Branded 404 |
| `netlify.toml` | Build + headers + 404 redirect |
| `_redirects` | Friendly URL aliases (`/brief`, `/thanks`) |
| `robots.txt` | SEO |
| `sitemap.xml` | SEO |
| `img/` | Hero + OG card |

## Deploy

Connected to Netlify. Push to `main` auto-deploys. See `DEPLOY_NOTES.md` (in this folder, not committed by default) for the one-time setup runbook.

## Source of truth

Editing copy or design? Edit the source files in:
`C:\zbd\03_PROJECTS\ZBD_Solutions\Assets\launch-page\`

Then sync to this folder before committing.

## Calendly placeholders

Replace `https://calendly.com/zimconsulting/zbds-*` URLs once event types exist. See `DEPLOY_NOTES.md` for the swap procedure.

## Analytics

Plausible script is commented out in `index.html` + `brief.html`. Uncomment after creating the Plausible property. 8 tagged events already wired via `plausible-event-name=` classes.

# Pro Master Wallcovering Website

Static multi-page website for Pro Master Wallcovering.

## Pages

- `index.html`
- `services.html`
- `projects.html`
- `about.html`
- `contact.html`

## Deployment

Upload all files in this folder to the public directory of the hosting provider.

The contact form uses FormSubmit and sends requests to:

`Santiago.echeverria@promasterwallcovering.com`

The first live submission may require email confirmation from FormSubmit before messages are delivered.

## Vercel

Deploy the repository root. The before/after project images must stay committed in:

`assets/projects/`

The HTML and CSS use root-relative paths such as `/assets/projects/park-town-renovation-before-1.jpg`, which work correctly on Vercel when the root directory is this project folder.

## Notes

- The site is written in English for a Canadian client.
- Project before/after photos are stored locally in `assets/projects`.
- General decorative images are loaded from Unsplash CDN.
- No build step is required.

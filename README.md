# TNKVIE Static Site

A static HTML/CSS/JS landing page for TNKVIE.

## Files

- `index.html` — main landing page
- `styles.css` — all styling
- `script.js` — mobile nav, reveal animation, and form email fallback
- `privacy.html` — privacy policy starter
- `terms.html` — terms starter

## Launch locally

Open `index.html` in your browser.

## Deploy on GitHub Pages

1. Create a GitHub repository.
2. Upload these files to the root of the repository.
3. Go to **Settings → Pages**.
4. Choose **Deploy from branch**.
5. Select the `main` branch and `/root`.
6. Save.

## Form setup

The audit form currently opens an email draft to `hello@tnkvie.com`.

For production, connect the form to one of these:

- Formspree
- Web3Forms
- Netlify Forms
- Your own FastAPI backend

Replace the form behavior in `script.js` when you connect a real form endpoint.

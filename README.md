# Sudip Pathak — Portfolio

A responsive, static portfolio website built with HTML, CSS and vanilla JavaScript. It is ready to deploy on Vercel without a build step.

## Before publishing

Update these placeholders in `index.html`:

1. Replace `YOUR_EMAIL@example.com` with your public contact email.
2. Replace the two footer `href="#"` values with your GitHub and LinkedIn profile URLs.
3. Replace the two project placeholder cards with real projects, including accurate descriptions and links.
4. Review the name and professional details to make sure you want them public.

## Preview locally

Open `index.html` in a browser, or run a local static server from this folder:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy to Vercel

### Option A — GitHub (recommended)

1. Extract this ZIP.
2. Create a new GitHub repository and upload the files in this folder.
3. Sign in to Vercel and choose **Add New → Project**.
4. Import the GitHub repository.
5. Keep the Framework Preset as **Other**.
6. Leave Build Command and Output Directory empty; the site is static.
7. Click **Deploy**.

### Option B — Vercel CLI

Install Node.js, then run:

```bash
npm install -g vercel
cd sudip-portfolio
vercel
```

Follow the prompts. Use `vercel --prod` when you are ready to publish to production.

## Notes

- No framework or package installation is required.
- The Google Fonts import requires an internet connection; system fonts remain as fallbacks.
- The contact email and social links are intentionally placeholders because no public contact details were provided.

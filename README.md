# Avon Beauty Studio — Website

Static site. No build step, no backend.

## Folder
- index.html      → the site
- assets/         → video, logo, photos
- vercel.json     → caches assets (optional)

## Deploy to Vercel

### Option A — CLI (fastest, no GitHub needed)
1. Install Node.js, then in this folder run:  npx vercel
2. Log in when prompted, accept the defaults.
3. For the live (production) URL:  npx vercel --prod

### Option B — GitHub + Dashboard (auto-deploys on every push)
1. Push this folder to a GitHub repo.
2. vercel.com → Add New → Project → import the repo.
3. Framework Preset: Other. Leave Build Command and Output Directory blank.
4. Deploy.

## Updating later
Replace any file in /assets with the same filename (e.g. a real hero.mp4
or new logo.png) and redeploy. To change the phone number, find/replace
919036905657 in index.html.

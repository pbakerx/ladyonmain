# The Georgian Lady on Main — Listing Landing Page

Single-page real estate landing page for the 1901 Georgian home on Main Street,
presented by Debra Penrod (Metro Brokers of Oklahoma).

## Contents

- `index.html` — the entire site (styles inline, no build step)
- `lady-on-main.mp3` — the song played by the "Hear Me Sing" player
- `vercel.json` — cache/range headers for the audio file

## Deploy to Vercel

**Option A — drag and drop (no tools needed):**
1. Go to https://vercel.com/new
2. Drag this whole `lady-on-main-site` folder onto the page
3. Click Deploy. Done — you'll get a `*.vercel.app` URL to share.

**Option B — Vercel CLI:**
```bash
npm i -g vercel
cd lady-on-main-site
vercel --prod
```

No framework, no build command, no environment variables. When Vercel asks,
the project is a plain static site (Framework Preset: "Other").

## Before going live

- Replace the two "See the House Listing" hrefs in `index.html`
  (marked with `TEMPORARY LINK` comments) with the real listing URL.
- Replace the four stand-in Wikimedia photos in the story section
  with actual listing photography.
- Logos load from debrapenrod.com's image host (static.wixstatic.com);
  for full self-hosting, save them into this folder and update the two
  `<img>` tags in the footer.

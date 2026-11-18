# Aarvi's Magical First Birthday Invitation

A mobile-first, single-page birthday invitation website.

## Event details included
- Aarvi's First Birthday
- 1 December 2026
- 6:00 PM – 10:00 PM
- HOTEL HEERA CRYSTAL INN, Dampier Nagar, Mathura

## Preview locally
Open `index.html` in a browser. For best results, run a local static server:
- Python: `python -m http.server 8000`
- Then open `http://localhost:8000`

## Publish free with Vercel
1. Extract this ZIP.
2. Create a GitHub repository and upload all files/folders from this project.
3. Sign in to https://vercel.com using GitHub.
4. Choose **Add New → Project**, import the repository.
5. Framework preset: **Other**. Build command: leave blank. Output directory: `.`.
6. Click **Deploy**. Vercel will give you a public invitation URL.
7. In Vercel → Project → Settings → Domains, you can add a custom domain if you own one.

## Edit details
- Main invitation content: `index.html`
- Colours, fonts, layout: `style.css`
- Countdown date/time and RSVP message: `script.js`
- Replace the cartoon image at `assets/aarvi-cartoon.jpg` to use a different photo/illustration.

## Notes
- Countdown uses India Standard Time (Asia/Kolkata, UTC+05:30).
- RSVP buttons open WhatsApp with a pre-filled message. They do not send automatically.
- The music toggle plays a simple original synthesized chime; it does not use a copyrighted song.
- Google Maps directions open a search for the venue name and address.
- Google Fonts require an internet connection; fallback fonts are included.

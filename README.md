# Scandinavia Family Trip 2027

A single-page, responsive travel itinerary for a family trip to Bergen, Oslo, Copenhagen, and Stockholm (2–16 April 2027).

## Features

- **Day by Day** — daily travel timeline, country filters, travel details.
- **Reservations** — confirmed and pending travel bookings.
- **Budget** — confirmed spending in Thai baht, with editable USD → THB exchange rate.
- Print/PDF support and mobile-friendly layout.
- No sticky/frozen headers.

## Tech stack

Static HTML, CSS, and vanilla JavaScript. The entire site lives in [`index.html`](./index.html); no build step, environment variables, or database are required.

## Deploy on Vercel

1. Open [Vercel — New Project](https://vercel.com/new).
2. Import GitHub repository `patsichat/scandinavia-2027`.
3. Set **Framework Preset** to **Other**, keep **Root Directory** at `./`, and leave Build Command empty.
4. Select **Deploy**. Production deployments will then follow pushes to `main` if Git integration is enabled.

## Data notes

- This website contains an itinerary and costs intended for sharing. Do not add passports, government IDs, booking confirmation codes, or other personal credentials to this public repository.
- Departure times and future transport bookings marked *to book* or *TBD* need rechecking before travel.
- Budget totals include confirmed items only; the USD → THB exchange rate is adjustable.

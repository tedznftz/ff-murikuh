# FF Murikuh — The Trophy

A single-page site for the FF Murikuh fantasy football league: champions history, standing rules, and amendments up for a vote — digitized as a trophy case.

Static HTML/CSS/JS, no build step, no backend. Data (season records, rules, votes) persists client-side via `localStorage`, with an optional pull from a published Google Sheets CSV for form submissions.

## Deploy

Any static host works. On Netlify: connect this repo, publish directory `.`, no build command (already configured in `netlify.toml`).

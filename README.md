# World Cup 2026 Match Centre

Single-file, JavaScript-only live tracker for the FIFA World Cup 2026.

- Fixtures and results by date (local timezone), all 72 group matches
- Collapsible group standings, computed client-side from results
- Official knockout bracket overview; slots auto-fill as groups complete
- Scores fetched in the browser from ESPN's public scoreboard API on load/refresh
- No build step, no backend — deploys as a static site

## Deploy

Vercel: import this repo at vercel.com/new (zero config), or `npx vercel --prod`.

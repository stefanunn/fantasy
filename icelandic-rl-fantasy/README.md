# Icelandic RL Fantasy (Season 10)

A zero-backend fantasy league web app for the Icelandic Esports League (Rocket League) with leagues, captain boost, budget rules, and a local-only leaderboard sync.

## Run locally
```bash
npm install
npm start
```

## Deploy on Vercel
- Push this folder to a GitHub repo.
- In Vercel: New Project → Import your repo → Deploy.
- Uses Tailwind CDN from index.html (no Tailwind build step required).

## Notes
- Budget: 100,000 kr.
- Roster: 5 starters, max 2 from the same real team.
- Scoring: 5 per Goal, 3 per Assist, 1 per Save. Captain: 1.5×.
- Weekly lock: Saturdays 12:00 UTC (before Sunday gameweek).
- League flow: Create/Join by code → Build team → Set captain → Enter stats → Publish to league.

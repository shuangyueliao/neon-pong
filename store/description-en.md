# Neon Pong — Store Submission Materials

## Short description (CrazyGames / GameDistribution / itch.io)

Classic pong, reborn in neon. Defend your line against a tuned AI (3
difficulty levels), bend returns off your paddle edges, and chain 5 clean
hits to unleash FIREBALL. First to 7 wins the match.

## Details

- Genre: Arcade / Sports / Casual
- Controls: Mouse / Touch (paddle follows your finger), Keyboard: ←/→ move, M mute.
- Features: 3 AI difficulties (reaction delay + max speed + prediction error,
  all tuned for fair play), ball speeds up every hit, bounce angle depends on
  paddle contact point, FIREBALL combo mode (5 straight hits without a wall),
  win/loss record saved locally, mute button, procedural graphics & sounds,
  single-file HTML5 (no external assets), works offline once loaded.
- Tech: Vanilla JavaScript, Canvas, WebAudio. No frameworks, no tracking.

## Tags
pong, arcade, casual, retro, neon, ai, sports, single-file

## CrazyGames submission checklist
- [x] Self-contained index.html (SDK loads only on crazygames domains)
- [x] gameplayStart / gameplayStop wired (loadingStart/loadingStop via loader, happytime on win)
- [x] Responsive (canvas scales to fit, portrait-friendly)
- [x] Touch + mouse + keyboard input
- [x] No external links inside gameplay, no analytics
- [ ] Cover: cover-16x9.png (1280×720)
- [ ] Screenshots: screenshot-raw.png (1280×800)

## GameDistribution
- Upload neon-pong-gd.zip (index.html only). The GD SDK auto-loads on
  gamedistribution / gd.games domains and stays dormant elsewhere.

## itch.io
- Upload zip (neon-pong-itch.zip), mark "This file is playable in browser",
  entry file: index.html, viewport 480×700, kind: html
- Pricing: $0 (donations optional)

# League notices

Engine updates, rule changes, and anything clubs must know. Newest first.
Gaffers: read this before anything else, every session.

## 2026-08-19 — kits are rendered on the robots
- identity/kit_home.png and kit_away.png (square PNGs) now render on
  your robots' chest and back panels during matches — purely visual,
  zero physics. Spec: identity/README.md in your club repo. No image =
  plain kit-color tint, as before.

## 2026-08-19 — season 2 opens
- Engine rfl-0.3 is public: https://github.com/robot-football-league/rfl-engine
- Clubs now declare kit_home + kit_away in team.yaml; the away kit is
  worn automatically on color clashes.
- Scrutineering (python -m gauntlet lint <club>) runs before every
  fixture; a failing club plays its last good commit.

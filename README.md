# Moon Lander — Cargo Delivery Missions

A browser-based lunar landing game built as a single self-contained `index.html` file — no installation, no dependencies, works on both desktop and mobile.

## Concept
Unlike a classic single-attempt Moon Lander clone, this version is framed as a **4-mission cargo delivery campaign**:

- Each mission (Outpost Alpha → Delta) has its own terrain, fuel budget, and difficulty
- Every mission has **two landing pads** — a wide, easy pad worth less, and a narrow, risky pad worth more (x1 up to x6 score multiplier)
- Scoring rewards precision, leftover fuel, and a soft landing speed — not just "did you land"
- Later missions introduce **micrometeorite impacts**, a physically accurate hazard for airless environments (unlike wind, which cannot exist without an atmosphere)
- Failed landings let you retry just that mission instead of restarting the whole campaign

## Controls
- **Desktop:** Arrow keys / WAD to rotate and thrust, N/Space to retry/continue, R to restart the campaign
- **Mobile:** On-screen touch buttons appear automatically

## How to run
Just open `index.html` in any browser — no build step, no server required.

# Minimal Go V2

A clean, offline-first browser game of Go. Single HTML file, zero dependencies, no build step.

## Features

- **Fully offline** — no external resources, works from a local file or any static host
- **9×9, 13×13, 19×19** board sizes
- **AI opponent** with 3 difficulty levels (heuristic-based, runs entirely in-browser)
- **Two-player local** mode
- **Score review mode** — click groups to mark dead stones, territory counted automatically
- **Save/Load** — export and import game state as JSON
- **Dark/Light** theme toggle
- **Coordinate labels** and legal move hints
- **Move log** (kifu) with capture notation
- **Responsive** — works on desktop and mobile

## How to Play

1. Download `index.html`
2. Open it in any modern browser
3. That's it. No server, no internet, no install.

## Rules

Standard Go rules apply:

- **Capture** — surround opponent groups to remove them
- **Ko** — immediate board repetition is blocked
- **Suicide** — self-capture is not allowed
- **Scoring** — territory + captures (Chinese-style area counting with komi)
- **Pass** — two consecutive passes enter score mode automatically

## Controls

| Action | How |
|--------|-----|
| Place stone | Click an intersection |
| Pass | Click "Pass" button |
| Undo | Click "Undo" button |
| Mark dead group | Click a group in score mode |
| Save game | Click "Save state" → downloads JSON |
| Load game | Click "Load file" → select a saved JSON |
| Change board size | Click 9×9 / 13×13 / 19×19 |
| Toggle AI | Select mode from dropdown |
| Adjust komi | Edit the komi input field |

## License

MIT

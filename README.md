# Quantum Gambit

**Every chess game becomes art.**

Quantum Gambit is a single-file chess game that runs entirely in your browser. Play against the built-in engine or import a PGN, and the game is drawn as artwork in seven styles you can export as PNG, SVG, GIF or a PDF poster.

> Built by a chess lover, for chess lovers.

## Features

- **Seven art styles:** Relativity, Quantum, Math, Fractal, Sketch, Manga and Technical. Captures, checks, castling and board control are all drawn in each style.
- **Play or import:** three engine levels (Novice, Club, Strong), or load any PGN. A famous game is built in.
- **Exports:** PNG, vector SVG, animated GIF and an A4 PDF poster with the player name and game details.
- **Board tools:** drag or click to move, right-click arrows and highlights, live material score.
- **History:** finished games and their art are saved in your browser.
- **Sound** with a mute switch, and screen-reader support for the position and moves.
- **Private and offline:** no accounts, no tracking, no subscriptions, no external requests. Fonts are embedded.

## Run it

Open `index.html` in any modern browser. Nothing to install or build.

## Deploy

It is a static site, so any static host works. For Cloudflare Pages, upload this folder (`index.html` and `_headers`) with no build command.

## Tech

Plain HTML, CSS and JavaScript. Canvas 2D for the board and art, a custom rules engine and PGN parser, negamax search with alpha-beta pruning, and hand-written SVG, GIF and PDF encoders. No dependencies.

## License

[MIT](LICENSE) © 2026 Quantum Gambit contributors

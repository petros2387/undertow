# Undertow

A grounded, first-person extraction shooter prototype. A drowned harbor city floods in surges every 75 seconds: the best salvage sits in the low streets, extraction points close as the water reaches them, and anything over 22 kg sinks you.

The current goal is to **prove the fun** of one decision: *one more crate, or get out before the tide?*

## Run it

Everything is in one file, `undertow.html`. Three.js and the fonts load from public CDNs, so you need an internet connection.

- Open `undertow.html` in Chrome, Edge or Firefox, or
- serve the folder locally, for example `python -m http.server 8765`, then open <http://localhost:8765/undertow.html>.

Progress (stash, money, loadout, settings) is saved in the browser's local storage.

## Controls

| Key | Action |
| --- | --- |
| W A S D, mouse | Move, look |
| Shift / Space | Sprint / jump |
| Click / right click | Fire / aim down sights |
| R | Reload |
| 1 / 2 / 3 | Sling, back or holster weapon |
| E | Search a crate, body or bag |
| Tab | Gear screen (the raid keeps running) |
| 4 – 0 | Quick-use slots |
| G / H | Ditch heaviest item / treat wounds |

## What's in the build

- Tide that surges in 6 stages and floods extraction points; swimming and sinking by weight
- Scavenger AI, six guns (auto, semi, pump, bolt), armor and helmet with durability
- Tarkov-style grid inventory, secure pouch, quick-use bar, rendered item icons
- Between raids: persistent stash, market with drifting prices, sell-only exchange
- Survival: health, energy, water, pain, and timed stims and food effects

## Status

Prototype, single HTML file, no build step or automated tests yet. Planning (GSD) is in progress.

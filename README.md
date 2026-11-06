# Build Your Own Idle Game in Godot

**Live:** https://sonusario.github.io/build_your_own_idle_game_in_godot/

A click-by-click tutorial, packaged as an installable offline PWA, that takes a Godot novice from an empty project to a published idle game ("Sprout Empire", in the spirit of Cookie Clicker).

- **Core loop first:** clicking, generators, upgrades, the shop, number formatting.
- **Saves:** JSON saves with safe writes and backups, versioning and migration, offline progress, export/import codes.
- **Standard idle features:** prestige, achievements, buffs, buy ×1/×10/×100/Max, settings, audio, particles, juice.
- **Assets:** making and using basic pixel, vector or painted art, then Blender, music and SFX.
- **Publishing and updating:** Web, Windows, macOS, Linux, Android and iOS, on itch.io, GitHub Pages, web portals, Steam, Google Play and the App Store.
- **Tour of Godot:** a broad pass over the engine features an idle game is most likely to use.
- **Mini games:** an in-game arcade of eight short games (platformer, top-down shooter, daily maze with pathfinding, pinball with joints, rhythm, drag and drop, 3D runner, split-screen duel) that explore the corners of Godot an idle game never reaches.
- **Branching:** choose your OS, platforms, stores, screen shape, art style, version control and monetization, and the tutorial shows only the steps for your path.

Godot concepts are linked to the official docs as questions ("What is a node?") instead of being re-explained. Written for Godot 4.5+.

Everything lives in `index.html`; `sw.js`, `manifest.webmanifest` and the icons make it a PWA. Progress checkboxes and your path are stored locally in your browser.

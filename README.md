# BlockCraft — Infinite Voxel Sandbox

A single-file Minecraft-like voxel game built with **Three.js**, featuring infinite procedural terrain generation, day/night cycles, mob AI, crafting systems, and building mechanics.

## Features

- **Infinite Chunk Generation** — Procedural terrain using simplex noise
- **Full Crafting System** — 2x2 and 3x3 crafting tables
- **Day/Night Cycle** — Dynamic sky and lighting
- **Mobs** — Passive (cows, pigs, chickens) and hostile (zombies, skeletons)
- **Building & Mining** — Break and place blocks
- **Health & Hunger** — Survival mechanics with hearts and food
- **HUD** — Hearts, hotbar, FPS counter, biome info
- **Inventory Management** — Full inventory grid with drag-and-drop
- **Audio** — Procedural sound effects

## Controls

| Key | Action |
|-----|--------|
| WASD | Move |
| Space | Jump |
| Left Click | Break block / Attack |
| Right Click | Place block |
| E | Inventory |
| 1-9 | Hotbar slots |
| Shift | Sprint |

## Tech Stack

- **Three.js** (via CDN module)
- **Vanilla JavaScript** (ES6+)
- **Procedural Audio** (Web Audio API)

## Usage

Open `blockcraft.html` in any modern browser. No build step required.

## Debug Hooks

Press `F1` to toggle debug info, or access `window.__game` for live inspection.

---

Built by [mwbreur](https://github.com/mwbreur)

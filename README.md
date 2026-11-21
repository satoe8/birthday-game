# ALI-A // 21st Birthday Edition

A custom 2D pixel-art web platformer and interactive cake decorator built as a 21st birthday gift.

**Live Demo:** https://allison-birthday.vercel.app/

## Features
- **Zero-Dependency Engine:** Self-contained HTML5 Canvas + Vanilla JavaScript with 60fps delta-time physics, coyote time, jump buffering, and double-jump mechanics.
- **Procedural Pixel Art:** Custom sprite matrices rendered at runtime onto offscreen canvases (player character, floating plushie companion, collectibles, and hazards).
- **Initiator Recon & Lag Mechanics:** Includes a sonar Recon Flash ability to reveal hidden platforms and stun hazards, alongside periodic `999ms` high-ping rubber-banding events.
- **Hybrid Audio System:** Web Audio API procedural chiptune soundtrack and SFX with HTML5 `<audio>` finale playback and automatic synth fallback.
- **Cross-Platform Controls:** Supports keyboard (`A`/`D` or Arrows to move, `W`/`Space`/`Up` to jump, `E`/`Shift`/Click to flash) and responsive on-screen touch controls for mobile browsers.

## Run Locally
Serve the directory with any static HTTP server:
```bash
npx serve .

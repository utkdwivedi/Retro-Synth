# Retro-Synth 🎮🔊

A browser-based retro sound-effect generator that creates 8-bit game audio **in real time** using procedural synthesis — no pre-recorded audio files required.

Retro-Synth uses a JavaScript implementation of **sfxr-style procedural sound generation**. Waveforms, envelopes, frequency sweeps, and other parameters are calculated at runtime, so each interaction can generate a tweakable sound rather than replaying a static asset.

![Retro-Synth screenshot](./Screenshot%202026-07-13%20235304.jpg)

## 🚀 Live Demo

🔗 https://utkdwivedi.github.io/Retro-Synth/

> Enable GitHub Pages from **Settings → Pages → Deploy from a branch → main → / (root)**.

## ⚙️ How It Works

- `script.js` implements the procedural synthesis engine and uses the Web Audio API to generate sound at runtime.
- `index.html` provides the interface for triggering and configuring sounds.
- `style.css` provides the lightweight browser UI.
- No audio assets are required for sound generation — the audio is synthesized in the browser.

## 🧪 Run Locally

```bash
git clone https://github.com/utkdwivedi/Retro-Synth.git
cd Retro-Synth
```

Then open `index.html` in a modern browser.

## 💡 Why Procedural Audio?

Traditional SFX libraries replay pre-recorded samples. Procedural synthesis instead constructs the sound mathematically, making it possible to vary parameters and create different retro-style effects interactively.

## 🛣️ Possible Next Steps

- Add one-click presets for pickup, laser, explosion, and jump sounds
- Add a randomize button for rapid sound exploration
- Export generated sounds as `.wav` files
- Add shareable sound parameter URLs

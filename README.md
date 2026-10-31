# Unknown Guitar Toolkits

Landing page for a set of free, open-source tools for guitarists. Everything runs on your own machine.

| Tool | What it does | Runs in |
|---|---|---|
| [TabLens](https://github.com/un4ckn0wl3z/TabLens) | Turns guitar tab images (scans, screenshots, text tab) into Guitar Pro 5 files | Browser |
| [Riff Forge](https://github.com/un4ckn0wl3z/riff-forge) | Builds drums and bass from a Guitar Pro riff; exports MIDI and WAV | Browser |
| [Tempo Bench](https://github.com/un4ckn0wl3z/tempo-bench) | Detailed metronome plus song practice with GP / MIDI / audio files and click-track export | Browser |
| [Solo Smith](https://github.com/un4ckn0wl3z/solo-smith) | Generates playable guitar solos in the key of your backing track; tab, Guitar Pro, MIDI and WAV | Browser |
| [Guitar Stem Studio](https://github.com/un4ckn0wl3z/guitar-stem-studio) | Splits a real song into 6 stems so you can mute the guitar and play along | Windows / macOS app |

How they connect:

- **Start from a tab:** tab image → TabLens → `.gp5` → Riff Forge → drums + bass (MIDI / WAV) → Tempo Bench
- **Start from a backing track:** key · scale · chords → Solo Smith → solo tab (`.gp`) → Tempo Bench
- **Start from a recording:** MP3 / YouTube → Guitar Stem Studio → stems / backing track → Tempo Bench

## The page

`index.html` is a single static page (Thai / English, light and dark). Screenshots of each app are in `assets/`. Enable GitHub Pages (Settings → Pages → Deploy from a branch → `main` / root) and it is served at `https://un4ckn0wl3z.github.io/unknown-guitar-toolkits/`.

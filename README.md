# Modern Luxury Hub — 256x Futuristic Luxury Resource Pack
**Minecraft Java Edition 26.3 · resource pack format 97.1 · v1.0.0**

Turns a multiplayer hub into a future luxury resort: polished Calacatta and Nero marble, brushed titanium, champagne gold, smoked and frosted architectural glass, carbon fibre, walnut and white oak, integrated LED lighting, calm natural landscaping, and a matching graphite-and-pearl interface.

## Contents
| Path | What it is |
|---|---|
| `ModernLuxuryHub-1.0.0-mc26.3.zip` | **Core pack.** Install this. No mods needed. |
| `ModernLuxuryHub-LabPBR-1.0.0-mc26.3.zip` | Optional shader add-on (LabPBR 1.3). Load it above the core pack. |
| `docs/` | INSTALLATION, COMPATIBILITY, TEXTURE_CATALOG, QC_REPORT, CHANGELOG |
| `previews/` | Before/after render, hub vignette, prototype sheet, per-category contact sheets |
| `source/` | The generator (Python + NumPy/SciPy/Pillow). Run `python3 -m lux.build` to rebuild every texture |
| `SHA1SUMS.txt` | Checksums for `server.properties` |

## Editions
- **Core:** everything that works in vanilla. The planned *Premium* tier was folded into Core, because splitting it would only have meant withholding finished textures, with no technical benefit.
- **Ultimate:** Core plus the LabPBR add-on (normal, AO, height, smoothness, F0/metal IDs, porosity, SSS and emission), for Iris/OptiFine shaders.

## Status
All automated QC checks pass (see `docs/QC_REPORT.md`). **The pack has not yet been loaded and inspected inside Minecraft 26.3,** because that could not be done from the build environment. Treat v1.0.0 as a release candidate until that in-game pass is done.

## Preview images
The preview images are offline isometric renders made directly from the pack's texture files, with a vanilla comparison. They are **not** in-game screenshots.

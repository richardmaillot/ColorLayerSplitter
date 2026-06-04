# ColorLayerSplitter

**Split a layer's colors into separate layers — non‑destructively.**

ColorLayerSplitter is a Photoshop (UXP) plugin that automatically separates the colors of a
layer into several distinct, auto‑named raster layers, grouped together, without ever altering
or deleting the original layer. Ideal for screen printing, flat‑color illustration, and file prep.

## Features
- Detects the dominant colors of the active layer, with a palette preview.
- Adjustable number of colors, grouping tolerance, and edge cleanup.
- "100% opaque flats" (posterize) mode, or anti‑aliasing preservation.
- "Ignore white / white background" option.
- Layers named by color (hex + RGB) and grouped automatically.
- Fully non‑destructive — the original layer is always kept.
- Bilingual English / French interface.

## Installation
1. Download the latest `ColorLayerSplitter.ccx` from the [Releases](../../releases) page.
2. Double‑click the file — Creative Cloud Desktop installs it into Photoshop.
3. In Photoshop, open the panel from the menu: **Plugins > ColorLayerSplitter**.

> Also available on the Adobe Creative Cloud Marketplace.

## Usage
Open a document, select a layer, click **Analyze**, adjust the settings if needed, then
**Split into layers**.

## Compatibility
Adobe Photoshop 23.3.0 or later — macOS and Windows.

## Privacy
This plugin collects no data. See [PRIVACY.md](PRIVACY.md).

## Author
Richard MAILLOT — Cryptomatte
© 2026

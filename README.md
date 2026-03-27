# BX Colour Selector

Welcome to `bx-colour-selector`.

This is a simple fullscreen HTML colour picker designed to make exploring colour values fast and pleasant. The page displays a full-screen colour field, shows the currently hovered HEX and decimal RGB values, and lets you copy the colour directly with the mouse.

## Live Demo

You can try the live demo here:

https://radimbrixi.github.io/bx-colour-selector/

## What It Does

- Shows a full-window colour spectrum
- Updates the browser tab title with the current HEX and RGB values
- Displays a live info label with the selected colour
- Shows a circular live preview swatch
- Copies the HEX value with left click
- Copies the decimal RGB value with wheel click

## How To Use

1. Open `index.html` in your browser.
2. Move your mouse over the page to inspect colours.
3. Left click to copy the HEX value.
4. Wheel click to copy the decimal RGB value.

## Files

- `index.html` - the complete self-contained colour selector

## Notes

The project is intentionally lightweight and does not require any build step, framework, or dependency installation.

If you are visiting this repository for the first time, you are very welcome here. I hope the tool is useful and easy to enjoy.

## Visitor Tracking

This project includes a ready-to-enable GoatCounter hook for privacy-friendly visitor tracking.

To turn it on:

1. Create a GoatCounter site.
2. Open `index.html`.
3. Set `window.BX_ANALYTICS.goatcounterUrl` to your GoatCounter count URL.

Example:

```html
goatcounterUrl: "https://your-code.goatcounter.com/count"
```

After that, GitHub Pages visitors will start being counted in your GoatCounter dashboard.

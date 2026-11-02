# Casefront

Marketing site for an AI intake and client-communication automation practice
serving small immigration and visa law firms.

## What this is

A single self-contained page. `index.html` contains the full site **and** the
interactive demo (embedded as a base64 data URL, rendered in a sandboxed
iframe overlay when you click "Try the live demo").

There is no build step, no dependencies, and no server. Upload and it works.

## Hosting

Served with GitHub Pages from the `main` branch, root folder.
Live at: https://yuviii27.github.io/casefront/

`.nojekyll` is present so GitHub Pages serves the file as-is instead of running
it through Jekyll.

## Editing

Everything lives in `index.html`:

- Copy, pricing tiers, FAQ — plain HTML
- Styling — one `<style>` block at the top, CSS custom properties in `:root`
- The demo — the `DEMO` base64 string near the bottom, and the overlay script
  directly above it

The demo source is also kept as `demo.html` in the parent project if you want to
edit it and re-embed.

## Contact

Yuvraj · yuviiiyuviii27@gmail.com · https://cal.com/who-yuviii/30min

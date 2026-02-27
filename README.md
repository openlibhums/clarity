# Clarity

A more modern theme for Janeway with a switchable colour palette system and accessibility improvements over the Clean theme.

## Installation

Clone or copy this theme into `src/themes/`, restart the server, then select **Clarity** under General Settings.

## Repository Support

Clarity includes repository (preprint) front-end templates. To enable them, add a local copy of the `REPOSITORY_THEMES` setting to your `settings.py` that includes `clarity`:

```python
REPOSITORY_THEMES = [
    "OLH",
    "material",
    "clarity",
]
```

## Colour Palettes

Clarity ships with five palettes: `evergreen`, `ocean`, `cardinal` and `midnight` (dark mode). To switch, edit the `@import` line near the top of `clarity.css`:

```css
@import url('/static/clarity/css/evergreen.css');
```

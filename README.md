# Bubblegum for Omarchy

A light pink-and-lilac theme with berry accents, pastel landscapes, and a matching Omarchy wordmark. Install it on a regular Omarchy desktop; Omarchy Kids is not required.

![Bubblegum on the desktop, with a pale pink bar and a cherry-blossom landscape](preview.jpg)

The preview was captured on an Omarchy Kids desktop. Its additional parental-control widgets are separate from this theme.

## Install

Run this from your regular Omarchy desktop session:

```bash
omarchy theme install https://github.com/peterholko/omarchy-bubblegum-theme.git
```

The installer downloads and activates **Bubblegum**. It then appears in Omarchy's theme selector. This theme uses the current `colors.toml` theme format; Omarchy generates the application configurations from its palette.

## Included

- A light palette with a soft pink background and berry accent.
- Six landscape wallpapers: Spring Meadow, Sunset Ridge, Blossom Dawn, Flower Valley, Lake Twilight, and Starlight Lake.
- The `Yaru-magenta` icon preference, using the icons supplied by Omarchy.
- Pink lighting on keyboards supported by Omarchy's theme controls.
- Matching unlock artwork and a preview, available under **Style → Unlock**.
- A landscape-and-wordmark screensaver.

Use **Super + Ctrl + Space** to cycle the wallpapers. Select the matching unlock artwork separately under **Style → Unlock**.

## Update

Update this theme and reapply it:

```bash
git -C "$HOME/.config/omarchy/themes/bubblegum" pull --ff-only
omarchy theme set bubblegum
```

## License

[MIT](LICENSE), with the original Omarchy copyright notice retained. See [attribution](ATTRIBUTION.md) for the source of the theme and preview.

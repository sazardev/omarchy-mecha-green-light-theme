# Mecha Green Light

![Mecha Green Light](preview.png)

**Sand, olive ink and bronze with flat topographic wallpapers for Omarchy light mode.**

## Install

```sh
omarchy theme install https://github.com/sazardev/omarchy-mecha-green-light-theme
omarchy theme set "Mecha Green Light"
```

## Included

- `colors.toml` and `shell.toml` for the complete light theme.
- btop, Chromium, icon and keyboard colour configuration.
- Seven native 3840×2160 (4K) lossless WebP wallpapers.
- Six clean 8-second native 4K H.264 live wallpaper loops.
- `0-topographic-light.webp` as the default.

## Wallpapers

| Set | Designs |
|---|---|
| Default | `0-topographic-light` |
| Collection | `100-drift-light`, `101-fold-light`, `102-field-light`, `103-terrain-light`, `104-panorama-light`, `105-undulate-light` |

Every asset is rendered directly from the original SVG artwork without upscaling.
Live loops animate only the contour lines; the Geist wordmark stays fixed.

## Login and boot screens

Install the matching SDDM login and Plymouth splash:

```sh
sudo bash -c "$(curl -fsSL https://raw.githubusercontent.com/sazardev/omarchy-mecha-green/main/system/install-login.sh)"
```

The installer backs up your configuration and rebuilds the initramfs.

## Full project

[`sazardev/omarchy-mecha-green`](https://github.com/sazardev/omarchy-mecha-green) adds the dark theme, HUD widgets, CLI tools, wallpaper generators and system-screen sources.

## License

MIT. See [LICENSE](LICENSE).

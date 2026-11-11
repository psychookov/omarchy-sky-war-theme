# Sky War

A dark Omarchy theme: near-black space, azure blue accent, painted-style nebulae, planets and starships.
Three wallpapers, each with a short animated intro that plays once and settles on the still.

All artwork (nebulae, stars, planet, ship designs) is original and procedurally generated.
No characters, logos or artwork from third-party franchises.

## Install

```bash
omarchy theme install https://github.com/psychokk/omarchy-sky-war-theme
omarchy theme set sky-war
```

Cycle wallpapers with `omarchy theme bg next`. Intros play at boot, on theme switch and when picking a
background. Turn them off with `omarchy theme bg intro disable`.

## What's inside

- `colors.toml`: palette (drives terminal, Waybar, Walker, Mako, Hyprlock, SwayOSD, btop and more)
- `backgrounds/`: `1-frota.webp`, `2-planeta.webp`, `3-nebulosa.webp` (2560x1440)
- `backgrounds/intros/`: matching `.mp4` intros (6.5 s, 2560x1440, 24 fps, H.264) ending on the still
- `icons.theme`, `preview.png`

## Palette

| Role | Color |
|---|---|
| background | `#06080b` |
| foreground | `#cfd6e0` |
| accent | `#4a9eff` |
| cursor | `#7cc0ff` |
| muted | `#5d6675` |

## Notes

Intros only cost extra power while they play; afterwards the still is shown.
The theme follows the documented Omarchy 4 layout but has not been verified on a live install yet.
Please open an issue if something looks off.

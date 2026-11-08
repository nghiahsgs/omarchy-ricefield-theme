# Ricefield

A dark Omarchy theme inspired by a peaceful Vietnamese village at dusk: bamboo shadows, rice-paper text, golden harvests, terracotta roofs, and lotus-pink accents.

![Vietnamese village at dusk](backgrounds/ricefield-dusk.png)

## Palette

| Color | Hex | Inspiration |
| --- | --- | --- |
| Background | `#18251f` | Bamboo shadows |
| Foreground | `#e9dfc5` | Rice paper |
| Accent | `#d8b568` | Harvest gold |
| Green | `#a6bd78` | Rice paddies |
| Orange | `#cf8b72` | Terracotta roofs |
| Magenta | `#c79baa` | Lotus petals |
| Blue | `#8eafbd` | Dusk sky |

## Use locally

Copy this repository to `~/.config/omarchy/themes/ricefield`, then apply:

```sh
omarchy theme set ricefield
```

Once published, install using the repository's GitHub URL:

```sh
omarchy theme install https://github.com/YOUR_USERNAME/omarchy-ricefield-theme
```

Replace `YOUR_USERNAME` with the publishing account.

## Coverage

`colors.toml` supplies the shared palette. Omarchy generates configurations for supported terminals, desktop components, editors, and tools using its installed templates. Exact application coverage depends on the Omarchy version. Active window borders use harvest gold; inactive borders use subdued green.

`icons.theme` selects the existing Yaru-sage icon set, which must be installed. This repository does not bundle an icon pack.

## Wallpaper

`backgrounds/ricefield-dusk.png` is an AI-generated original made for this theme using OpenAI's built-in image generation tool. The prompt is recorded in [WALLPAPER.md](WALLPAPER.md). The wallpaper preview above is artwork, not a desktop screenshot.

## Distribution

Publish this as a standalone public repository named `omarchy-ricefield-theme`, following Omarchy's theme naming convention. See the [official theme guide](https://learn.omacom.io/2/the-omarchy-manual/92/making-your-own-theme) for installation and community-listing instructions.

## License

Theme configuration and documentation: MIT. The generated wallpaper is provided under the same terms to the extent applicable rights exist. Yaru icons remain under their upstream licenses.

# trunorthinteractive.github.io

The website for TruNorth Interactive, an independent game studio. It is served by GitHub Pages at
https://trunorthinteractive.github.io.

## Pages

| Path | File | What it is |
| --- | --- | --- |
| `/` | `index.html` | Studio homepage: logo, games list. |
| `/mrk1/` | `mrk1/index.html` | MRK1 game page: key art, wishlist button, about, screenshots. |
| `/about/` | `about/index.html` | About the studio and Matthew Church. |

## Layout

```
index.html          Homepage
mrk1/index.html     MRK1 page
assets/style.css    Shared styles: colours, aurora background, layout
assets/*.png        Logo, MRK1 key art and screenshots
```

Plain HTML and CSS, with no build step and no JavaScript. The only outside resource is the
Silkscreen pixel font from Google Fonts.

## Editing

- **Colours** are CSS variables at the top of `assets/style.css`. The studio palette comes from
  the logo; the MRK1 page uses its own red and violet (`--mrk-red`, `--mrk-violet`).
- **Aurora background:** `body::before` and `body::after` in `assets/style.css`. Change their
  `opacity` to make it brighter or fainter. It stops moving for visitors who have reduced motion
  turned on.
- **Social links** are pixel-art SVG icons in the footer of each page. The footer is copied in
  both pages, so change both.
- **Adding a game:** copy `mrk1/` to a new folder, then add a card for it to the Games section of
  `index.html`.
- **Steam link:** the wishlist button in `mrk1/index.html` links to `#` until the store page is
  live.

## Previewing

Open `index.html` in a browser. Links between pages work from the file system.

## Publishing

Merge to `main`. GitHub Pages deploys from `main` (Settings → Pages) and the site updates within
a minute or two.

## Contact

- Email: trunorthinteractive@gmail.com
- [Instagram](https://www.instagram.com/trunorthinteractive/) ·
  [TikTok](https://www.tiktok.com/@trunorthinteractive) ·
  [YouTube](https://www.youtube.com/@trunorthinteractive) ·
  [Twitch](https://www.twitch.tv/trunorthinteractive)

## Licence

Code in this repository (HTML and CSS) is MIT licensed; see `LICENSE`. All images, logos, game
assets and written content are © TruNorth Interactive, all rights reserved.

# HG + UG Family Diwali Magazine 2026

## Open offline

Extract the entire ZIP. Open `index.html` in Chrome or Edge. Keep `assets`, `vendor`, and all other files together. No installation, internet connection, or server is needed.

Desktop: a centered single front cover, two-page inside spreads, and a centered single back cover. Narrow phones show one page at a time so the design stays readable.

Hover over a photo/video to reveal its button. On touch screens, tap once to reveal and again to open. Originals open in a full-size viewer; videos have playback controls. Escape closes the viewer. Arrow keys and on-screen arrows turn pages. The Pages button opens thumbnails.

## Publish on GitHub Pages

1. Put the contents of this folder at the root of your GitHub repository, including `assets`, `vendor`, and `.nojekyll`.
2. Use GitHub Desktop or Git to upload the folder. GitHub's browser uploader has a smaller per-file limit than Git.
3. In repository Settings → Pages, choose **Deploy from a branch**, select your branch and **/ (root)**, then Save.
4. Open the Pages URL GitHub provides. Relative asset paths also work under a repository subpath.

Published on GitHub Pages at https://vvivek3024-glitch.github.io/hg-ug-diwali-magazine-2026/

## Design and media

All 14 page images preserve the supplied PDF. The pink boxes on pages 10 and 11 contain the Mahila Mandal heading, subtitle, and description. No visible extra photos or autoplaying videos are layered over the design.

`media.js` contains percentage-based clickable areas. `media-map.json` records each original source filename and its packaged filename. Photos are copied from the supplied archive. Videos come from the supplied magazine-video archive. One source video larger than GitHub's 100 MB file limit has been re-encoded with H.264/AAC at its original frame dimensions; the source archive remains unchanged.

The bundled StPageFlip 2.0.7 library matches the version in the supplied source archive. Its MIT license is included under `vendor/LICENSE`. There are no CDN, font, analytics, or external runtime dependencies.

The online edition uses optimized H.264/AAC videos (up to 720 pixels on the longest side, 30 fps). Full clips and audio are retained. The separate offline ZIP is unchanged.

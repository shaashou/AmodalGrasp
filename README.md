# AmodalGrasp — website workspace

This repository starts from the [SceneComplete project website](https://github.com/scenecomplete/scenecomplete.github.io).
It is a website template/workspace for AmodalGrasp; the original SceneComplete text, figures, videos, paper, and 3D assets are currently retained as placeholders and are **not AmodalGrasp results**.

## Current state

- Original page layout and example assets copied from the upstream `main` branch on 2026-11-25.
- Original MIT license and LERF template attribution retained.
- Upstream ClustrMaps visitor-tracking identifier removed.
- GitHub Pages is intentionally not enabled yet. Replace the project content before publishing.

## Files to replace

| File or folder | Content |
| --- | --- |
| `index.html` | Title, authors, affiliations, abstract, links, captions and citation |
| `script.js` | Scene navigation and interactive viewer behavior |
| `style.css` | Page styling |
| `static/3d/` | Interactive scene meshes |
| `static/images/` | Figures, thumbnails and videos |
| `static/paper/` | Paper PDF |

Keep each example's attribution until it is replaced. Do not present the upstream scientific results as AmodalGrasp results.

## Local preview

From this directory, run:

```sh
python -m http.server 8876 --bind 127.0.0.1
```

Then open <http://127.0.0.1:8876/>. Some fonts, scripts and the model-viewer runtime are loaded from the original external services, so this is not a fully offline bundle.

## Credits

Source: [SceneComplete](https://scenecomplete.github.io/), copyright (c) 2024 scenecomplete, under the retained [MIT license](LICENSE).
The upstream page credits [LERF's website](https://www.lerf.io/) as its layout source. Its existing footer attribution has been preserved.

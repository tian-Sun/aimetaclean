# AI MetaClean — project notes

A standalone, English-language overview of [AI MetaClean](https://aimetaclean.org/), an image metadata inspection and cleaning tool.

**Published overview:** https://tian-sun.github.io/aimetaclean/

## What this repository contains

- `index.html` and `styles.css`: a buildless, responsive project overview.
- `assets/`: the project icon and two real product captures using a synthetic demonstration image. There is no personal image data.
- `.nojekyll`: serves the static files directly on GitHub Pages.

This is the source of the **overview page only**, not the cleaning application. Publishing this repository does not open-source the app or grant a license to its source code. There are no analytics, forms, tracking parameters, third-party fonts, or scripts on this page.

## Preview

From this directory:

```sh
python3 -m http.server 4173 --bind 127.0.0.1
```

Open http://127.0.0.1:4173/ in a browser. No dependencies or build step are needed.

## Publish

GitHub repository Settings → Pages → Deploy from a branch → `main` → `/ (root)`.

Only this directory belongs in the public Pages repository. Do not copy the parent project's source, `.env` files, private operational notes, or Git history.

## Scope

The live tool supports JPG, PNG, and WebP. Original-format cleaning preserves supported encoded image and display data; format export re-encodes. Removing supported metadata is not removal of visible watermarks or pixel-embedded signals such as SynthID, and is not a guarantee that image origin cannot be detected.

This is a substantive product overview, not an automatic redirect or a replacement domain for bypassing another site's moderation. [Show HN guidelines](https://news.ycombinator.com/showhn.html) ask for something people can try and specifically exclude landing pages; submit the working product only when the account and site are eligible.

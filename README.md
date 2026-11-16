# Photobone download site

Small bilingual landing page for the Photobone Windows test build. The scroll fades, SVG fallback, and page layout use plain HTML, CSS and JavaScript. The hero includes an optional WebGL contour layer using React Three Fiber and `@react-three/postprocessing`; pinned modules load from esm.sh. If the module or WebGL context is unavailable, the animated SVG remains as a fallback.

## Run locally

Open `index.html` in a browser. The download button points to `downloads/Photobone-Test-Build.zip`.

## Publish with GitHub Pages

Put this folder's contents at the root of a GitHub repository, then select **Settings → Pages → Deploy from a branch → `main` / `/(root)`**. GitHub Free Pages requires a public repository. See [GitHub Pages setup](https://docs.github.com/en/pages/quickstart).

The page and package are an experiment. Keep the “vibecoded · just a test” notice visible if you edit the design. See `THIRD-PARTY-NOTICES.md` for dependency attribution.

<div align="center">

<img src="huff-icon.jpg" alt="HUFF symbol" width="180">

# HUFF WEB

**A real-time video instrument for working with moving images.**

Load video or use a camera. Shape the image with live effects, feedback, compositing, and spatial transformations.

| [**REFERENCE ↗**](https://schwwaaa.github.io/huff-web/reference/) | [**GITHUB ↗**](https://github.com/schwwaaa/huff-web) | [**TRY NOW ↗**](https://schwwaaa.github.io/huff-web/) |
|:---:|:---:|:---:|

`VIDEO` · `FEEDBACK` · `COMPOSITING` · `LIVE PROCESSING`

</div>

---

## THE INSTRUMENT

HUFF Web is an interactive video-processing instrument for exploring motion, image transformation, and feedback. Begin with a camera or video file, arrange effects, adjust their controls, and experiment with the resulting image.

This repository also contains the HUFF Web landing page and an illustrated control reference.

## EXPLORE THE INTERFACE

The [website](https://schwwaaa.github.io/huff-web/) includes a GUI walkthrough with screenshots and brief descriptions. Select any GUI image to enlarge it, or browse the individual annotated reference pages below.

**[OPEN THE REFERENCE LIBRARY ↗](https://schwwaaa.github.io/huff-web/reference/)**

| CONTROLS | WHAT THEY DO |
|:---|:---|
| [**SOURCE ↗**](reference/source/index.html) | Choose a camera or video file and manage playback and the source image. |
| [**PRESETS ↗**](reference/presets/index.html) | Save, recall, and reset effect configurations. |
| [**PIPELINE ↗**](reference/pipeline/index.html) | Arrange the stages of image processing. |
| [**VISTA ↗**](reference/vista/index.html) | Reposition moving regions drawn from video frames. |
| [**PANELING ↗**](reference/paneling/index.html) | Divide the frame into bands or a field of independently transformed panels. |
| [**SYMMETRY ↗**](reference/symmetry/index.html) | Mirror the image and adjust the axis of reflection. |
| [**GLOBAL MIX ↗**](reference/global-mix/index.html) | Combine processed and source imagery with blend controls. |
| [**FEEDBACK ↗**](reference/feedback/index.html) | Reintroduce previous frames to create image trails and accumulation. |
| [**LUMA KEY ↗**](reference/luma-key/index.html) | Use brightness to control masking and compositing. |
| [**SOLARIZE ↗**](reference/solarize/index.html) | Alter tones using threshold and color-channel controls. |
| [**SIFT ↗**](reference/sift/index.html) | Displace and distort the image with swirl and turbulence. |
| [**ABOUT & CAPTURE ↗**](reference/about-capture/index.html) | View application information and capture window, 16:9, 4:3, or 9:16 screenshots. |

## WATCH

A selection of HUFF demonstrations is embedded in the [website's video carousel](https://schwwaaa.github.io/huff-web/).

## WEBSITE FILES

The included website is static HTML, CSS, JavaScript, and local image assets. Its landing page is `index.html`; the reference library starts at `reference/index.html`.

To view a local copy, serve the repository directory using a simple HTTP server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000/`. This command serves the website files; it is **not** an installation or build command for the HUFF Web instrument itself.

## PROJECT LINKS

**[TRY NOW](https://schwwaaa.github.io/huff-web/)** · **[REFERENCE LIBRARY](https://schwwaaa.github.io/huff-web/reference/)** · **[SOURCE REPOSITORY](https://github.com/schwwaaa/huff-web)** · **[SCHWWAAA](https://linktr.ee/schwwaaa)**

---

<div align="center"><sub>HUFF WEB · SCHWWAAA</sub></div>

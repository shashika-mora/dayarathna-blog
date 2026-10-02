# dayarathna-blog

Technical engineering journal and architectural reflections for Shashika Dayarathna, deployed at [blog.dayarathna.com](https://blog.dayarathna.com).

## Scope & Status

This repository hosts personal technical essays, systems architecture investigations, and development retrospectives.

- **Current Status**: Upcoming journal with planned topics. No articles are published yet. Articles will be published directly as they are completed without synthetic or filler content.
- **Editorial Focus**: Operating systems, low-level architecture, clean software design, and engineering retrospectives.

## Architecture

- **Stack**: Pure semantic HTML5, pure CSS3, and vanilla ES6+ JavaScript.
- **Visual System**: Celestial space aesthetic, dark palette (`#070a10`), neon lime accents (`#c7f44a`), typography (`DM Sans`, `IBM Plex Mono`, `Instrument Serif`), and hardware-accelerated HTML5 Canvas starfield.
- **Dependencies**: Zero runtime dependencies, zero build steps.
- **Hosting**: Firebase Hosting targeting site `shashika-dev-blog` under project `shashika-dev`.

## Authoring & Edit Workflow

1. To add an article or update editorial sections, edit `index.html`.
2. Static assets (images, schematics) belong in `public/`.
3. Test locally by running any static web server (e.g. `python -m http.server 8080` or `npx serve .`).
4. Validate responsive layouts on mobile, tablet, and desktop viewports.

## Deployment

Deploy strictly to the dedicated blog hosting site:

```sh
npx firebase-tools deploy --only hosting:blog --project shashika-dev
```

## Maintainer

Maintained by Shashika Dayarathna. Main portfolio: [https://dayarathna.com](https://dayarathna.com).

# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Personal website for Thorben Hellweg, hosted on GitHub Pages at www.thllwg.de.

## Tech Stack

- Static HTML (no build system, no frameworks)
- Single CSS file: `assets/css/style.css`
- No JavaScript

## Site Structure

```
index.html              → Home page
about/index.html        → About page
notes/index.html        → Notes listing
notes/kasanka/index.html → Individual note (Zambia article)
assets/css/style.css    → All styles
```

## Development

Edit HTML and CSS files directly. No build step required.

## Deployment

Push to `master` branch — GitHub Pages auto-deploys. Custom domain configured via `CNAME` file.

## Adding a New Note

1. Create a new directory under `notes/` (e.g., `notes/new-topic/`)
2. Add `index.html` with the article content
3. Add a link to `notes/index.html`

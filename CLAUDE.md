# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is Fei Wang's personal GitHub Pages site (`wangfe.github.io`). It uses Jekyll with the `jekyll-theme-minimal` theme and is deployed automatically via GitHub Actions on every push to `main`.

## Deployment

Deployment is fully automated — pushing to `main` triggers the Jekyll build and deploy workflow (`.github/workflows/jekyll-gh-pages.yml`). There is no manual build or deploy step needed.

Two workflows exist:
- `jekyll-gh-pages.yml` — builds with Jekyll then deploys (primary)
- `static.yml` — deploys raw static files without a Jekyll build step

## Local Preview

To preview the site locally with Jekyll:

```bash
gem install bundler jekyll
jekyll serve
```

The site will be available at `http://localhost:4000`.

## Site Configuration

- `_config.yml` — Jekyll settings (theme, title, description)
- `index.html` — main page content
- Theme: `jekyll-theme-minimal`

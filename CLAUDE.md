# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project state

This is a bare [Hugo](https://gohugo.io/) static site scaffold (created via `hugo new site`). It has no theme installed (`themes/` is empty), no content pages, and no custom layouts yet — `hugo.toml` only sets `baseURL`, `languageCode`, and `title`.

## Common commands

- `hugo server -D` — run the local dev server with drafts included (serves at `http://localhost:1313`).
- `hugo` — build the static site into `public/`.
- `hugo new content <path>` — create a new content file using the archetype in `archetypes/default.md`.
- `hugo new theme <name>` or `git submodule add <repo> themes/<name>` — install a theme (none is installed yet; `hugo.toml` will need a `theme = "<name>"` line to activate it).

## Structure

- `hugo.toml` — site configuration.
- `archetypes/` — front-matter templates used by `hugo new content`.
- `content/`, `data/`, `i18n/`, `layouts/`, `static/`, `assets/` — standard Hugo directories, currently empty.
- `themes/` — empty; no theme is installed.

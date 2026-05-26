# Yukino Notes

Personal production notes for Yukino's projects.

This repository is intended to become an Astro-powered notes site for:

- production logs
- design notes
- game development notes
- technical notes

Target site:

- `https://notes.yukinooooooosan.cc/`

The main profile site remains separate:

- `https://yukinooooooosan.cc/`

The profile site should stay as a static HTML/CSS/JS site. Notes content and
Astro-specific implementation should live in this repository.

## Development

```bash
npm install
npm run dev
```

Build the static site:

```bash
npm run build
```

Preview the built site:

```bash
npm run preview
```

## Content

Notes live in `src/content/notes/` as Markdown files.

Each note needs frontmatter:

```md
---
title: "Note title"
description: "Short summary for lists and metadata."
pubDate: 2026-05-26
tags:
  - project
draft: false
---
```

Draft notes are hidden from the public pages when `draft: true`.

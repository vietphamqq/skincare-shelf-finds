# skincare-shelf-finds

Website, blog and privacy policy for the Skincare Shelf Finds content project.
Live at: https://vietphamqq.github.io/skincare-shelf-finds

## Structure

- Jekyll site, built automatically by GitHub Pages on push to `main` — no Actions setup needed.
- Posts live in `_posts/YYYY-MM-DD-slug.md` with categories: `skin-types`, `ingredients`, `routine-basics`, `shelf-picks`.
- `privacy.html` and `terms.html` are static files (used by the Pinterest API app review) — do not convert them to Jekyll layouts.

## Adding a daily post

Create one file `_posts/YYYY-MM-DD-slug.md`:

```
---
layout: post
title: "..."
description: "One sentence, states the answer (max 160 chars)."
categories: [routine-basics]
date: YYYY-MM-DD
---
(850–1100 words, self-contained answer, h2 sections, ends with "## The short version" bullets)
```

Editorial rules: English for a US audience; the post fully answers what the title promises;
no medical/treatment claims; no invented stats or prices; no undisclosed affiliate links.

## Newsletter

`beehiiv_form_id` in `_config.yml` holds the beehiiv subscribe-form id; the signup box renders site-wide via `_includes/newsletter.html`. Clear the value to hide it.

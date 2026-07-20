# Melvin Paul — Product Builds Portfolio

A single-page portfolio site showcasing product builds, each with a full detail
screen: the problem, what was built, tech stack, status, and real screenshots
from the working products.

## Structure
- `index.html` — the entire site (routing, styles, and project data all live here)
- `images/` — screenshots referenced by each project's detail page

## Local preview
Just open `index.html` in a browser — no build step, no dependencies.

## Deploy
Connected to Vercel for automatic deployment on every push to `main`.

## Updating content
All project copy, stack tags, status labels, and screenshot references live in
the `PROJECTS` array near the top of the `<script>` tag in `index.html`. Edit
there, commit, and push — Vercel redeploys automatically.

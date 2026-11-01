# Netnoddy's Blog

This blog is built with Jekyll and GitHub Pages. Write each post as a Markdown file in `docs/`; pushing it to the `main` branch automatically rebuilds and publishes the site.

In the repository's **Settings > Pages**, set the publishing source to the `main` branch and `/docs` if it is not already configured.

## Write a post

Create a file in `docs/`, for example `docs/my-post.md`:

```markdown
---
title: "My post"
date: 2026-11-01
summary: One-line description shown on the homepage.
---

Write the post here using Markdown.
```

Commit and push the file to `main`. GitHub Pages will publish it automatically; the newest posts appear on the homepage. The `date` and `summary` fields are optional, but the front matter block (`---`) is required.

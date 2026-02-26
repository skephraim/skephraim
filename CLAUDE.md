# CLAUDE.md — AI Assistant Guide for skephraim/skephraim

## Repository Overview

This is a **GitHub profile repository** (`skephraim/skephraim`). GitHub treats this special repository by rendering its `README.md` directly on the public profile page at `https://github.com/skephraim`.

There is no application code, build system, or test suite. The sole purpose of this repository is to maintain the GitHub profile presentation.

## Repository Structure

```
skephraim/
└── README.md    # GitHub profile page content (rendered on https://github.com/skephraim)
```

## File Conventions

### README.md

- This file is the **profile page** — it is public-facing and visible to anyone who visits the GitHub profile.
- It uses standard **GitHub Flavored Markdown (GFM)**.
- The file currently uses GitHub's profile README template with emoji bullet points for personal info sections.
- The HTML comment block at the bottom (`<!--- ... --->`) is a GitHub template hint and can be removed once the profile is complete.

## Development Workflow

Since there is no code to build or test, the workflow is simple:

1. **Edit** `README.md` directly to update the profile content.
2. **Commit** with a clear message describing the profile change (e.g., `Update profile bio`, `Add skills section`).
3. **Push** to `main` — GitHub will immediately reflect the changes on the profile page.

### Branches

- `main` — the default branch; changes here are live on the profile page.
- Feature branches (e.g., `claude/...`) can be used for drafting profile updates before merging to `main`.

## Key Conventions for AI Assistants

1. **Do not add application code** — this repo is intentionally content-only.
2. **Keep README.md profile-focused** — it should represent the user personally (interests, learning goals, contact, etc.).
3. **Respect emoji usage** — the existing style uses emoji in bullet points; maintain this style if editing.
4. **No build/lint/test steps** — there are no commands to run. Changes are validated visually on GitHub.
5. **Fill in placeholder sections** before committing if asked to update the profile — don't leave `...` placeholders in the final content.
6. **Markdown only** — no HTML beyond what GitHub's markdown renderer supports in READMEs (basic `<img>`, `<a>`, alignment divs are acceptable).

## Common Tasks

| Task | Action |
|------|--------|
| Update bio / interests | Edit the bullet list in `README.md` |
| Add GitHub stats badges | Insert a `![GitHub Stats](https://github-readme-stats.vercel.app/...)` image link |
| Add a skills section | Add a new `## Skills` heading with badge images or a list |
| Add social links | Add icon+link badges (e.g., using `shields.io`) |
| Preview changes | Push to a branch and view the branch's README on GitHub, or use a local Markdown previewer |

## Notes

- GitHub profile READMEs support a limited subset of HTML — avoid JavaScript, `<script>`, or `<style>` tags.
- Large images or animated GIFs can slow down profile page load; prefer optimised assets.
- The profile README has no size requirement, but concise and scannable layouts tend to perform better visually.

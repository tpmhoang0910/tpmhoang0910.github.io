<<<<<<< HEAD
# tpmhoang0910.github.io
=======
# tpmhoang0910.github.io

Personal website of Pham Minh Tri Hoang, built with the [al-folio](https://github.com/alshedivat/al-folio) Jekyll theme (MIT license).

Live site: https://tpmhoang0910.github.io

## Where to edit

| What | File |
| --- | --- |
| Name, site description, URL | `_config.yml` |
| Home page bio and photo settings | `_pages/about.md` |
| Profile photo | `assets/img/bio.jpg` |
| CV page content | `_data/cv.yml` |
| Social links (email, LinkedIn, GitHub) | `_data/socials.yml` |
| News items on the home page | `_news/*.md` (one file per item) |
| Publications | `_bibliography/papers.bib` |

## Run locally (Docker)

```bash
docker compose pull
docker compose up
```

Then open http://localhost:8080. Stop with Ctrl+C.

## Publish

Push to the `main` branch. The "Deploy site" GitHub Action builds the site into the `gh-pages` branch, which GitHub Pages serves.
>>>>>>> 0d5a95e (First version of my website)

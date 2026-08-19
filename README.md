# tingyu-zhou.github.io

Personal academic website for Tingyu Zhou, Professor and J. Harold & Barbara M.
Chastain Eminent Scholar Chair in Real Estate, Florida State University.

Live at <https://tingyu-zhou.github.io>.

Built on the [Academic Pages](https://github.com/academicpages/academicpages.github.io)
Jekyll template (MIT). Migrated from Google Sites in August 2026.

## How to edit

Everything is plain Markdown. Edit a file, commit, and GitHub rebuilds the site
in about a minute.

| To change | Edit |
|---|---|
| Home page / bio | `_pages/about.md` |
| Working papers | `_pages/working-papers.md` |
| Teaching | `_pages/teaching.md` |
| Presentations | `_pages/presentations.md` |
| Service | `_pages/service.md` |
| Awards and grants | `_pages/awards-grants.md` |
| Site title, sidebar, links | `_config.yml` |
| Header menu | `_data/navigation.yml` |

### Publications

Each article is one file in `_publications/`, named `YYYY-MM-DD-slug.md`. The
Publications page is generated from those files, newest first. To add a paper,
copy an existing file and change the fields.

The date drives the sort order only. The year is real; the month encodes the
display order carried over from the original Google Site.

To attach a PDF, put it in `files/` and link to
`https://tingyu-zhou.github.io/files/yourfile.pdf`.

# Yesutorwu Dzidzornu — Research & Projects

Public homepage: https://yesutorwu.github.io/

This is the personal research hub. The existing MRI case study remains at https://yesutorwu.github.io/mri-segmentation-research/.

## Pages
- `index.html`: introduction and featured work
- `projects.html`: project directory
- `about.html`: background and research interests
- `updates.html`: milestones and next steps
- `assets/style.css`: responsive visual styles

GitHub Pages serves `main` from the repository root. No build step or paid service is required. Images currently use the already-public MRI website asset URLs; keep that repository available or copy the approved display images here before retiring it.

## Add another project
1. Create a dedicated project page or project site.
2. Copy the `article.project` block in `projects.html` and replace its title, image, description, status, and link.
3. If appropriate, feature it on `index.html`.
4. Add a dated update to `updates.html`. Distinguish planned work from completed results.
5. Preview, check links and mobile layout, commit the changes, and publish to `main`.

Use only approved public figures. Keep raw MRI, datasets, atlases, credentials, private correspondence, and collaborator data outside this repository. No license granting reuse is added by default.

## Local preview
Run `python3 -m http.server 8766 --bind 127.0.0.1` in this directory, then open http://127.0.0.1:8766. Stop with Ctrl+C.

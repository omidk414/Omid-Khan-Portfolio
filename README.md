# Omid Khan — Quarto Portfolio

A responsive dark-themed portfolio built with Quarto, custom CSS, and vanilla JavaScript.

## Preview locally

1. Install [Quarto](https://quarto.org/docs/get-started/).
2. Open this folder in VS Code or a terminal.
3. Run `quarto preview`.

## Deploy to GitHub Pages

1. Copy the source files to your existing GitHub Pages repository.
2. Run `quarto render` to create the `docs/` directory.
3. Commit and push both the source files and the generated `docs/` directory.
4. In GitHub repository Settings → Pages, choose **Deploy from a branch**, branch **main**, folder **/docs**.
5. Update `website.site-url` in `_quarto.yml` to the actual GitHub Pages URL if it differs.

## Customization

- Edit content in `index.qmd`, `projects.qmd`, and `work_experience.qmd`.
- Edit colors and styling in `styles.css`.
- Edit particle animation and typewriter text in `effects.html`.
- Confirm all employment dates, educational credentials, and project metrics before publishing.

Note: The old `project.qmd` must be named `projects.qmd`, and the Quarto configuration filename must be `_quarto.yml`.


Certification cards added to `work_experience.qmd` under Professional Certifications.

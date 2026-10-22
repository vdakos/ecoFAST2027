# ecoFAST2027

Website and materials of ecoFAST2027, a tutorial and colloquium on the empirical quantification
of resilience and the identification of nonlinear changes in ecological systems (Montpellier,
22–23 March 2027, free of charge).

- Monday 22 March: tutorial on ecoFAST (dynamical Footprint Analysis, Shapes and Trends of
  ecological time series), an R package for detecting abrupt shifts and quantifying resilience
  in ecological data.
- Tuesday 23 March: colloquium of invited talks, open to all.

Website: <https://dynshift.github.io/ecoFAST2027/>

Organiser: Vasilis Dakos, Institut des Sciences de l'Évolution de Montpellier (ISEM), CNRS,
University of Montpellier ([vasilis.dakos@umontpellier.fr](mailto:vasilis.dakos@umontpellier.fr)).

## Contents

| Path | Content |
|---|---|
| `_quarto.yml`, `*.qmd`, `styles.css` | Source of the website (Quarto) |
| `images/` | Banner photo and partner logos |
| `docs/` | Rendered website, published with GitHub Pages |

Tutorial and colloquium materials (slides, exercises, data) will be added to this repository.

## Updating the website

Edit the `.qmd` files, run `quarto render` in this folder and commit the changes together with
`docs/`. GitHub Pages publishes the `docs/` folder of the `main` branch.

# attraction_bias

Code and texts are available in [paper.qmd](./paper/paper.qmd)

## Project Structure

```
attraction_bias/
├── data/               # Data files
├── paper/              # Paper source files
│   ├── paper.qmd       # Main paper document (Quarto)
│   ├── bibliography.bib # Bibliography
│   ├── preamble.tex    # LaTeX preamble
│   ├── elsarticle.cls  # Elsevier article class
│   ├── elsarticle-harv.bst # Harvard bibliography style
│   ├── typgloss.sty    # Typographic glossing package
│   └── _extensions/    # Quarto extensions
├── Makefile            # Build automation
└── README.md           # This file
```

## Building the Paper

```bash
# Build both HTML and PDF
make

# Build HTML only
make html

# Build PDF only
make pdf

# Publish to GitHub Pages
make publish

# Sync with Overleaf
make overleaf_branch

# Clean auxiliary files
make clean
```

## Requirements

- [Quarto](https://quarto.org/) (>= 1.2.198)
- LaTeX distribution (e.g., TeX Live, TinyTeX)
- R (for data analysis)
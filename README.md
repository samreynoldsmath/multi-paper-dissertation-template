# Multi-paper Dissertation Template

## Description
A multi-paper dissertation template for LaTeX.

A multi-paper dissertation is a dissertation that consists of multiple papers that have been published in peer-reviewed journals. This template attempts to conform to Portland State University's [ETD formatting requirements](https://www.pdx.edu/gradschool/etd-formatting-requirements) as of 2024.

## Instructions
1. Click the green "Use this template" button to create a new repository with this template.
2. Clone the repository to your local machine.
3. Edit `dissertation.tex` and the files in the `src` directory as you see fit.

## Tips
- You can clear the TeX build files with `git` by running
  ```bash
  git clean -ix .
  ```
- In a 12pt font LaTeX document, the following font sizes are available:
  | Command | Size |
  | --- | --- |
  | `\normalsize` | 12pt |
  | `\small` | 11pt |
  | `\footnotesize` | 10pt |
- Use `split` environments to split equations across multiple lines while preserving a single equation number.
- Search for `overfull` warnings in the `.log` file to find lines that are too long.

## See Also
- Other [LaTeX templates](https://github.com/samreynoldsmath/hdt-latex-templates)
- Organize your LaTeX preamble with [texmf](https://github.com/samreynoldsmath/texmf)

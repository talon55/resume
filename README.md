# A simple LaTeX project containing my resume and cover letter

**Note**: This repo is designed to take advantage of the compiling features provided
by the [LaTeX-Workshop](https://github.com/James-Yu/LaTeX-Workshop) VS Code
extension, and the [Multi-File projects](https://github.com/James-Yu/LaTeX-Workshop/wiki/Compile#multi-file-projects) tooling in particular.

## Installation

Compiling this repo requires a local LaTeX installation, including the following packages:
```
sudo apt install texlive-latex-base texlive-fonts-recommended texlive-fonts-extra texlive-latex-extra latexmk cm-super chktex
```

## Troubleshooting

Issues with fonts may come from malformed font map files. Use the following command to regenerate them:
```
sudo updmap --sys
```

# ALICE beamer theme for LaTeX

This is an unofficial ALICE theme for slides created with the LateX beamer class. It is adapted from [beamerthemeNord](https://github.com/junwei-wang/beamerthemeNord) by Junwei Wang which uses the [Nord](https://www.nordtheme.com/) color scheme. You can also find the Nord beamer theme on [CTAN](https://ctan.org/pkg/beamerthemenord) and [Overleaf](https://www.overleaf.com/latex/templates/beamerthemenord/xyjjhcsyyjbr).

## Install

**NOTE:** I use `lualatex` to build this project, though `xelatex` should also work. I'm not sure about other engines such as `pdflatex`, since (from what I understand) they do not support UTF-8 input. 

The simplest way to use this style is to copy all `.sty` files into the folder of your LaTeX project. If you want all your LaTeX projects to have access to this style without copying the files each time, you can follow these steps: 

- On Linux systems, create the following directories if they do not already exist (TeX doesn't create them by default): `$HOME/texmf/tex/latex/`.
- Copy all the `.sty` files in this repository into the directory you just created, or a subdirectory of it. You may also simply clone the entire repository. For example, you may have something like this: `$HOME/texmf/tex/latex/beamerthemeALICE/`.
- TeX should automatically search the home directory, so it should be able to find your custom style now. If not, you may need to explicitly specify the `TEXMFHOME` vairable and/or run (`sudo`) `texhash`. 

## License

Since this work is derived from [beamerthemeNord](https://github.com/junwei-wang/beamerthemeNord), we refer to the following: 

This work may be distributed and/or modified under the conditions of the LaTeX Project Public License, either version 1.3c of this license or (at your option) any later version. The latest version of this license is in http://www.latex-project.org/lppl.txt .

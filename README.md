# The xcolor-material package
The xcolor-material package is built on top of the great [xcolor](https://www.ctan.org/pkg/xcolor) package. It exists for providing a useful definition of the beautiful Google Material Color Palette, available from https://material.google.com/style/color.html, for its use in document writing with L<sup>A</sup>T<sub>E</sub>X and Friends.

## Installation
If the package is released on [CTAN](https://www.ctan.org/), the users should be able to install it through the TeX distribution package manager available on their PC. Nevertheless, if you need to install the package manually, you should run

    latex xcolor-material.ins

and copy the generated file `xcolor-material.sty` to a path where LaTeX can find it. To generate the documentation you should run the following command twice.

    pdflatex xcolor-material.dtx

## Copyright
Copyright (C) 2016 Jerick Órdenes

Released under the [LaTeX Project Public License](http://www.latex-project.org/lppl.txt) version 1.3 or later

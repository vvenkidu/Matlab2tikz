# Matlab2tikz

What software can we use to customize Matlab figures?

matlab2tikz:
Download the package from Matlab site.
https://www.mathworks.com/matlabcentral/fileexchange/22022-matlab2tikz-matlab2tikz
Place downloaded package into "bin"

Create a figure in matlab, use the package function
matlab2tikz('figure.tikz') to generate tex document.
Open that tex document in overleaf/latex to modify and customize figure.

``` Latex
\usepackage{pgfplots}
\usepackage{tikz}
```
pgfplots package can be used to format and edit figures using any data-set.

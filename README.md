# r-phylo

This repo contains resources for conducting phylogenetic comparative analyses.

The vignettes can be reproduced using the [remake](https://github.com/richfitz/remake) R package. This is available to download from github:
```
devtools::install_github("richfitz/remake")
```
To get all of the packages used in the vignettes, type
```
remake::install_missing_packages()
```
and to re-run all examples and analyses
```
remake::make("all")
```

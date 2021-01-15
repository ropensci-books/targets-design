# targets R package design specification

[![ropensci](https://badges.ropensci.org/401_status.svg)](https://github.com/ropensci/software-review/issues/401)
[![joss](https://joss.theoj.org/papers/10.21105/joss.02959/status.svg)](https://doi.org/10.21105/joss.02959)
[![zenodo](https://zenodo.org/badge/327033759.svg)](https://zenodo.org/badge/latestdoi/327033759)
[![status](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)
[![check](https://github.com/ropensci/targets-design/workflows/check/badge.svg)](https://github.com/ropensci/targets-design/actions?query=workflow%3Acheck)
[![publish](https://github.com/ropensci/targets-design/workflows/publish/badge.svg)](https://github.com/ropensci/targets-design/actions?query=workflow%3Apublish)

This repository contains the design specification of the [`targets`](https://github.com/ropensci/targets) R package. These specifications describe the internal architecture, the data storage model, and the orchestration and branching model. The goal is to help developers contribute to core elements of the package. The rendered output lives at <https://books.ropensci.org/targets-design>.

## Code of conduct

Please note that this package is released with a [Contributor Code of Conduct](https://ropensci.org/code-of-conduct/).

## Citation

```r
citation("targets.design")
#> The targets design specification is part of targets. To cite targets, see #> below:
#> 
#>   Landau, W. M., (2021). The targets R package: a dynamic Make-like
#>   function-oriented pipeline toolkit for reproducibility and #> high-performance
#>   computing. Journal of Open Source Software, 6(57), 2959,
#>   https://doi.org/10.21105/joss.02959
#> 
#> A BibTeX entry for LaTeX users is
#> 
#>   @Article{,
#>     title = {The targets R package: a dynamic Make-like function-oriented #> pipeline toolkit for reproducibility and high-performance computing},
#>     author = {William Michael Landau},
#>     journal = {Journal of Open Source Software},
#>     year = {2021},
#>     volume = {6},
#>     number = {57},
#>     pages = {2959},
#>     url = {https://doi.org/10.21105/joss.02959},
#>   }
```

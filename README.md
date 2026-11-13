# rlme

Rank-based estimation and prediction in two- and three-level random effects nested models.

Compatibility updates by Renova.

Version 0.5.9001 makes metadata changes only: the stale optional `Date` field was removed from `DESCRIPTION`, and the three authors are now also listed in an `Authors@R` entry with roles; the `Author` field reads `Yusuf Bilgic [aut, cre], Herb Susmann [aut], Joseph McKean [aut]` and the maintainer address is unchanged. No R, C++ or documentation file was changed.

## Install

From R-universe:

```r
install.packages("rlme", repos = c(
  Renova = "https://renova-r.r-universe.dev",
  CRAN = "https://cloud.r-project.org"
))
```

Or the exact release tag:

```r
install.packages("remotes")
remotes::install_github("renova-r/rlme@renova-0.5.9001")
```

[Release notes](NEWS.md) · [Renova package directory](https://github.com/renova-r/revival-catalog)

rlme was written by Yusuf Bilgic (maintainer), Herb Susmann and Joseph McKean. License: GPL (>= 2) (see [COPYING](COPYING)).

# Readme

Demo repository for a research paper written with the help of R, R Markdown, git, and GitLab as part of the EGU 2018 short course "Writing reproducible geoscience papers using R Markdown, Docker, and GitLab", see [https://vickysteeves.gitlab.io/repro-papers/](https://vickysteeves.gitlab.io/repro-papers/).

## Render article locally

```
library("rmarkdown")
draft("MyArticle.Rmd", template = "copernicus_article", package = "rticles")
render("MyArticle/MyArticle.Rmd")
```

## Run online

The GitLab repository is synced with a GitHub repo ([https://github.com/nuest/rticle-copernicus-demo](https://github.com/nuest/rticle-copernicus-demo)) for usage with Binder:

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/nuest/rticle-copernicus-demo/master)

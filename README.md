# RMarkdown Template for Focus Bioinformatics Reports 

This R package provides a LaTeX and RMarkdown template suitable for Focus
reports. The design and layout is loosly oriented at MS Word defaults. In the
YAML header of the RMarkdown template, you can easily customize the colors,
logos and cover page:

```
---
title: Document Title
author: Focus 
date: "`r format(Sys.time(), '%d de %B, %Y')`"
params:
  logo: logo.png
  cover: cover.png
  iblue: 41567D
  igray: d4dbde
documentclass: article
fontsize: 18
papersize: a4paper
...
---
```

## Installation

Install the package latex-report-template from GitHub. 

```r
# install.packages("devtools")
devtools::install_github("pedrosa-biomed/focus_reports")
```





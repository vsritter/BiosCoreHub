# BiosCoreHub

[![stability-experimental](https://img.shields.io/badge/stability-experimental-orange.svg)](https://github.com/mkenney/software-guides/blob/master/STABILITY-BADGES.md#experimental)

The goal of BiosCoreHub is to assist NC TraCS Bios Core analysts by providing basic reporting tools for the most common statistical analysis requests.

## Installation

You can install the released version of BiosCoreHub from GitHub with:

``` r
install.packages("devtools")
library(devtools)

install_github("vsritter/BiosCoreHub")
```

## Usage

Once installed, load the package with:

``` r
library("BiosCoreHub")
```

and the "TraCS report" template should be available.

You can create a new report in Rstudio doing *File > New File > R Markdown > From template > TraCS report \{BiosCoreHub\}*.


## Example

HTML report template

<img src="inst/screenshots/report_html.png" width="700" style="border: 1px solid black"/>

<br>

PDF report template

<img src="inst/screenshots/report_pdf.png" width="700" style="border: 1px solid black"/>

<br>

Docx report template

<img src="inst/screenshots/report_docx.png" width="700" style="border: 1px solid black"/>


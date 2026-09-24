P8105_HW1_zw3268
================
Zeheng Wei
2026-09-24

``` r
library(tidyverse)
```

    ## ── Attaching core tidyverse packages ──────────────────────── tidyverse 2.0.0 ──
    ## ✔ dplyr     1.2.1     ✔ readr     2.2.0
    ## ✔ forcats   1.0.1     ✔ stringr   1.6.0
    ## ✔ ggplot2   4.0.3     ✔ tibble    3.3.1
    ## ✔ lubridate 1.9.5     ✔ tidyr     1.3.2
    ## ✔ purrr     1.2.2     
    ## ── Conflicts ────────────────────────────────────────── tidyverse_conflicts() ──
    ## ✖ dplyr::filter() masks stats::filter()
    ## ✖ dplyr::lag()    masks stats::lag()
    ## ℹ Use the conflicted package (<http://conflicted.r-lib.org/>) to force all conflicts to become errors

## Problem_1

Importing the dataset

``` r
data("penguins", package = "palmerpenguins")
```

The `penguins` dataset includes information about penguins’ species,
island, sex, and year, along with measurements of bill length, bill
depth, flipper length, and body mass. It contains 344 observations and 8
variables. The mean flipper length is 200.915 mm.

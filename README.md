# transfermarktScraperRPackage

This R package is a web scraper for [transfermarkt.us](transfermarkt.us), which provides data and market values for all EPL and Championship players. 

## Installation

In your RStudio console:

```
install.packages("devtools")

library(devtools)

install_github("zlessner/transfermarktScraperRPackage");
```


## Usage

View the dataframe:

``` r
head(PLdata)


#>             Player     Country         Team 
#> 1           Alisson      Brazil Liverpool FC
#> 2 Caoimhin Kelleher     Ireland Liverpool FC
#> 3      Loris Karius     Germany Liverpool FC
#> 4            Adrián       Spain Liverpool FC
#> 5   Virgil van Dijk Netherlands Liverpool FC
#> 6   Ibrahima Konaté      France Liverpool FC ...

```
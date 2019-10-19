# r-packages
R Packages for Data Science

# Table of Contents

1.  [Development](#org53f17cd)
    1.  [Testing and Exceptions](#org1d21c8e)
    2.  [Utilities](#orgb934c8b)
2.  [Collection](#org405ce68)
3.  [Storage](#orgc37710d)
4.  [Data Structure](#org51d2f3f)
    1.  [Data Frames](#org278408c)
    2.  [Matrices](#orgc841107)
    3.  [Time Series](#orgfa213ff)
5.  [Databases](#orgd89a2cc)
6.  [Data Transformation](#orgbcd0ff5)
7.  [Data Validation and Cleaning](#orga068797)
8.  [Data Inspection and Summary](#org12ff94a)
9.  [Visualization](#org62154b8)
10. [Feature Transformation](#org9a8d9d6)
    1.  [Missing Data](#org34d4739)
    2.  [Optimal Transforms](#org4eec589)
    3.  [Factors](#org5cc8ddc)
    4.  [Representation Learning](#orgfa844d3)
11. [Feature Filtering and Dimension Reduction](#orgbc74538)
12. [Feature Selection and Importance](#org5356d76)
13. [Preprocessing](#orgb519d3c)
14. [Models and Statistics](#orge0e0765)
15. [Resampling](#orge8d4629)
16. [Hyperparameter Optimization](#org2d7ccfe)
17. [Performance](#org0b29e70)
18. [Interpretation](#orgf96c0cf)
19. [Report and Deploy](#orgefb7a2c)


<a id="org53f17cd"></a>

# Development

-   **devtools:** tools for package development
-   **usethis:** automated package tasks
-   **pacman:** package installation/loading utilities
-   **import:** import single functions from a package
-   **packrat:** reproducible development with local package installation
-   **jetpack:** lightweight dependency management for projects and local installs
-   **checkpoint:** install packages from a specific time and date
-   **config:** configuration file management


<a id="org1d21c8e"></a>

## Testing and Exceptions

-   **testthat:** 

-   **assertthat:** 


<a id="orgb934c8b"></a>

## Utilities

-   **butcher:** remove unneeded data from a model
-   **insight:** extract model parameters; see also other packages by the same author
-   **wrapr:** operators and environments
-   **zeallot:** destructuring assignment
-   **fastpipe:** efficient pipe operators


<a id="org405ce68"></a>

# Collection

-   **rio:** universal import and export
-   **opendata:** [Task View](https://github.com/ropensci/opendata)
-   **tabulizer:** pdf table scraping


<a id="orgc37710d"></a>

# Storage

-   **RData:** native dataframe storage
-   **RDS:** native R objects
-   **fst:** a fast read/write format, like feather
-   **archivist:** collections of objects for reproducibility


<a id="org51d2f3f"></a>

# Data Structures


<a id="org278408c"></a>

## Data Frames

-   **base::data.frame:** tabular data
-   **data.table:** efficient data frames
-   **tibble:** user-friendly data frames
-   **disk.frame:** for mid-sized data sets too large to fit in RAM


<a id="orgc841107"></a>

## Matrices

-   **Matrix:** 


<a id="orgfa213ff"></a>

## Time Series

-   **base::ts:** 

-   **zoo:** 

-   **xts:** comprehensive library for timeseries built on zoo
-   **tidyverts:** tidy tools for time series
-   **tsbox:** universal time series converter and utilites


<a id="orgd89a2cc"></a>

# Databases

-   **DBI:** for database connections
-   **dbplyr:** dplyr db interface
-   **rquery:** query generator


<a id="orgbcd0ff5"></a>

# Data Transformation

-   **dplyr:** piped data transformations
-   **dtplyr:** \`dplyr\` interface to \`data.table\`
-   **seplyr:** evaluation extensions for dplyr
    Quoted evaluation, evaluation partitioning.
-   **cdata:** generalized pivots using data description
-   **forcats:** categorical transformations
-   **stringr:** string manipulation


<a id="orga068797"></a>

# Data Validation and Cleaning

-   **validate:** powerful validation framework with error localization, imputation, and reporting
-   **janitor:** common cleaning operations
-   **dataMaid:** common checks and report generation
-   **OpenRefine:** Java app for cleaning and formatting
-   **rrefine:** R interface to OpenRefine
-   **assertr:** similar to validate but more lightweight
-   **OfficialStatistics:** CRAN view


<a id="org12ff94a"></a>

# Data Inspection and Summary

-   **inspectdf:** text summary and plots
-   **visdat:** data visualization
-   **UpSetR:** intersecting set visualization
-   **corrplot:** 

-   **base::head:** 

-   **utils::str:** 

-   **dplyr::glimpse:** 

-   **base::summary:** summary statistics
-   **skimr:** text summary
-   **HMisc::describe:** text summary
-   **finalfit::ff<sub>glimpse</sub>:** text summary
-   **DescTools:** Abstract and Describe, text summary and plots
-   **DataExplorer:** text summary and plots, reporting


<a id="org62154b8"></a>

# Visualization

-   **base:** 

-   **lattice:** 

-   **vcd:** categorical plots in a lattice framework
-   **ggplot2:** see [here](https://www.ggplot2-exts.org/index.html) for a list of extensions
-   **cowplot:** various extensions to ggplot, themes, formatting, gridplot of all classes
-   **GGally:** various extensions to ggplot, model diagnostics, formatting, and more
-   **ggExtra:** marginal plots for ggplot
-   **ggpmisc:** various extensions, drawing on plots, time series with peaks and valleys , stat plots with embedded statistics
-   **WVPlots:** explanatory and comparison plots in ggplot; "prescribed presentations"
-   **ggfortify:** \`autoplot\` for a large number of packages
-   **ggRandomForests:** 


<a id="org9a8d9d6"></a>

# Feature Transformation


<a id="org34d4739"></a>

## Missing Data

-   **naniar:** (check out the vignettes, too)
-   **VIM:** imputation of NA data and visualization its distribution
-   **mice:** multiple imputation
-   **MissMech:** tests for the nature of missingness
-   **finalfit:** various plots and reports


<a id="org4eec589"></a>

## Optimal Transforms

-   **acepack:** regression transform selection
-   **homals:** optimal scaling transforms
-   **aspect:** optimal scaling transforms
-   **vtreat:** "y-aware" scaling


<a id="org5cc8ddc"></a>

## Factors

-   **factorMerger:** factor response clustering


<a id="orgfa844d3"></a>

## Representation Learning


<a id="orgbc74538"></a>

# Feature Filtering and Dimension Reduction


<a id="org5356d76"></a>

# Feature Selection and Importance

-   **vip:** variable importance plots
-   **varImp:** variable importance for random forests


<a id="orgb519d3c"></a>

# Preprocessing

-   **vtreat:** 

-   **recipes:** 

-   **mlrCPO:** 


<a id="orge0e0765"></a>

# Models and Statistics

-   **nns:** nonlinear nonparametric statistics with partial moments; classification, clustering and regression, correlation and dependence, forecasting
-   **forecast:** 

-   **smooth:** 


<a id="orge8d4629"></a>

# Resampling

-   **vtreat:** has CV index generating functions
-   **sampler:** 


<a id="org2d7ccfe"></a>

# Hyperparameter Optimization

-   **mlrMBO:** 

-   **IRACE:** 

-   **mlr:** 
-   **dials:** 


<a id="org0b29e70"></a>

# Performance

-   **performance:** 

-   **plotmo:** residuals, response, partial dependence
-   **visreg:** regression plots
-   **car:** regression plots
-   **gamlss::wp:** wormplots


<a id="orgf96c0cf"></a>

# Interpretation

-   **DrWhy:** comprehensive collection of tools for exploration and interpretation
    [homepage](https://modeloriented.github.io/DrWhy/)
    [github](https://github.com/ModelOriented/DrWhy) - a great resource; lots of interesting and useful packages
    [Predictive Models: Explore, Explain, Debug](https://pbiecek.github.io/PM_VEE/) - book by the authors of DrWhy
-   **DALEX:** local and global interpretation of variables
    [tutorial](http://uc-r.github.io/dalex)
-   **iml:** local and global interpretation of variables with interaction support
    [tutorial](http://uc-r.github.io/iml-pkg)
-   **LIME:** local interpretation of variables
    [tutorial](http://uc-r.github.io/lime)


<a id="orgefb7a2c"></a>

# Report and Deploy

-   **finalfit:** creates formatted tables of many types
-   **dashR:** R interface to plotly's Dash framework
-   **shiny:** 


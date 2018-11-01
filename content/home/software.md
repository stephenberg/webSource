+++
# Custom widget.
# An example of using the custom widget to create your own homepage section.
# To create more sections, duplicate this file and edit the values below as desired.
widget = "custom"
active = true
date = 2016-04-20T00:00:00

# Note: a full width section format can be enabled by commenting out the `title` and `subtitle` with a `#`.
title = "Software"
subtitle = ""

# Order that this section will appear in.
weight = 60

+++
* [GitHub](https://github.com/stephenberg)

* The <tt>automultinomial</tt> package, for regression models (similar to logistic regression) of spatially correlated discrete data.  [Vignette](/software/automultinomial/vignette.pdf) with detailed description and guide to use. Available for download on 
[cran](https://cran.r-project.org/web/packages/automultinomial/index.html) and   [GitHub](https://github.com/stephenberg/automultinomial) 
<img src = "/software/automultinomial/plotk2.png", width = "200", height = "200">

* The <tt>bcd</tt> package. This is a c++ implementation (with R wrappers via Rcpp) of block coordinate descent for fitting group lasso penalized linear (logistic, multinomial, Poisson, multiresponse linear) regression models. It supports the overlapping group lasso without explicit duplication of the columns of the design matrix, and sparse design matrices. Available for download on [GitHub](https://github.com/stephenberg/bcd).
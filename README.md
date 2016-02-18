# `NFPdata` R Package

This repository holds the gene ontology based gene similarity data package. The data within this package are able to be used with the methods in `NFP` R package.

There are only one dataset in this package right now:

* `geneSimData` - KEGG gene semantic similarity based on Gene ontology.

# Install Instructions (All platforms)

To install the `NFPdata` package, we have devised a different deliver mechanism than is used to install the `NFP` R package containing the methods. The different delivery mechanism was required due to the large size (25mb + and gaining!) of the data  associated within this package violating policy setforth by [CRAN](https://cran.r-project.org/web/packages/policies.html). Please note that installing the `NFPdata` package with this delivery mechanism as safe as the install process associated with the `NFP` R package via CRAN. (Some would argue it is more secure...)

To install the package with an internet connection you can either use:

```r
# Install R devtools
install.packages("devtools")

# Install the package from github
devtools::install_github("yiluheihei/NFPdata")
```

Alternatively, you can call an installation method within the `NFP` R package:

```r
NFP::load_geneSimData()
```

# Licensing

GPL 2.0.

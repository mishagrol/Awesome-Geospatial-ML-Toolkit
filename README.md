# Awesome Environmental Geospatial [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/mishagrol/Awesome-Environmental-Geospatial)

[![GitHub stars](https://img.shields.io/github/stars/mishagrol/Awesome-Environmental-Geospatial)](https://github.com/mishagrol/Awesome-Environmental-Geospatial/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/mishagrol/Awesome-Environmental-Geospatial)](https://github.com/mishagrol/Awesome-Environmental-Geospatial/network)
![GitHub contributors](https://img.shields.io/github/contributors/mishagrol/Awesome-Environmental-Geospatial)
![GitHub last commit](https://img.shields.io/github/last-commit/mishagrol/Awesome-Environmental-Geospatial)
[![GitHub license](https://img.shields.io/github/license/mishagrol/Awesome-Environmental-Geospatial)](https://github.com/mishagrol/Awesome-Environmental-Geospatial/blob/master/LICENSE)


Awesome Environmental Geospatial is a curated collection of cutting-edge tools, resources, and projects that harness the power of geospatial technologies to address pressing environmental challenges. From GIS applications for habitat conservation to remote sensing techniques, this repository showcases the intersection of environmental science and spatial analysis. Whether you're a researcher, practitioner, or enthusiast, dive into this repository to discover innovative solutions for sustainable resource management, conservation planning, and environmental monitoring.

**Please contribute. Let's make this guide better!** Please follow the [Contributing Guidelines](https://github.com/mishagrol/Awesome-Environmental-Geospatial/blob/master/Contribute.md). Or you can open issue: [Welcome to contribute](https://github.com/mishagrol/Awesome-Environmental-Geospatial/issues/)

Inspired by [Awesome Python](https://github.com/vinta/awesome-python).

**Table Of Contents:**
- [Awesome Environmental Geospatial ](#awesome-environmental-geospatial-)
  - [General analysis](#general-analysis)
  - [Imbalance data](#imbalance-data)
  - [Spatial autocorrelaton](#spatial-autocorrelaton)
  - [Uncertainty quantification](#uncertainty-quantification)
  - [Modeling](#modeling)
  - [Reference](#reference)


----
## Geospatial ML
In environmental monitoring and natural resource management, ML approaches offer unique opportunities for complex spatial solutions due to domains’ and scales’ adaptability and advantageous computational efficiency of methods. However, spatially distributed data describing environmental phenomena have specificity that introduces biases to the straightforward implementation of data-driven approaches. 
We suggest a pipeline for ML geospatial applications in environmental modeling and elaborate on critical aspects such as imbalanced data, spatial autocorrelation, prediction errors, and the nuances of model generalization, domain specificity, and uncertainty estimation.
Considering the dominant spread of Python and R as programming environments for data-driven modeling, including geospatial modifications, most of the libraries and packages we mention are made within these languages.

## General analysis
- [Simple Features (sf)](https://r-spatial.github.io/sf/articles/sf1.html) -  Reading, writing and converting Simple Features. Provides a set of tools for working with geospatial geometries represented by points, lines, polygons. <img height="20" src="img/R.png" alt="R">
- [sp](https://github.com/edzer/sp/) - R Classes and Methods for Spatial Data. <img height="20" src="img/R.png" alt="R">
- [raster](https://github.com/rspatial/raster) - A free and open source software tool that serves as an introduction to spatial data analysis. <img height="20" src="img/R.png" alt="R">
- [terra](https://github.com/rspatial/terra) - Provides methods to manipulate geographic (spatial) data in "raster" and "vector" form. <img height="20" src="img/R.png" alt="R">
- [geopandas](https://github.com/geopandas/geopandas) - GeoPandas is an open source project to make working with geospatial data in python easier. GeoPandas extends the datatypes used by pandas to allow spatial operations on geometric types. <img height="20" src="img/python.png" alt="Python">
- [rasterio](https://github.com/rasterio/rasterio) - Geographic information systems use GeoTIFF and other formats to organize and store gridded raster datasets such as satellite imagery and terrain models. Rasterio reads and writes these formats and provides a Python API based on Numpy N-dimensional arrays and GeoJSON. <img height="20" src="img/python.png" alt="Python">
- [gdal](https://github.com/OSGeo/gdal) - Presents a single raster abstract data model and single vector abstract data model to the calling application for all supported formats. It also comes with a variety of useful command line utilities for data translation and processing. <img height="20" src="img/c++.png" alt="C++">
- [pysal](https://github.com/pysal/pysal) - the Python spatial analysis library, is an open source cross-platform library for geospatial data science with an emphasis on geospatial vector data written in Python. It supports the development of high level applications for spatial analysis, such as. <img height="20" src="img/python.png" alt="Python">
  
## Imbalance data

- [imbalance](https://github.com/ncordon/imbalance) -  Provides a set of tools to work with imbalanced datasets: novel oversampling algorithms, filtering of instances and evaluation of synthetic instances. <img height="20" src="img/R.png" alt="R">
- [smotefamily](https://cran.r-project.org/web/packages/smotefamily/index.html) - A collection of various oversampling techniques developed from SMOTE is provided. <img height="20" src="img/R.png" alt="R">
- [themis](https://github.com/tidymodels/themis) - Contains extra steps for the recipes package for dealing with unbalanced data. <img height="20" src="img/R.png" alt="R">
- [Imbalanced-learn](https://github.com/scikit-learn-contrib/imbalanced-learn) - Python package offering a number of re-sampling techniques commonly used in datasets showing strong between-class imbalance. It is compatible with scikit-learn. <img height="20" src="img/python.png" alt="Python">
- [biomod2](https://github.com/biomodhub/biomod2) - computer platform for ensemble forecasting of species distributions, enabling the treatment of a range of methodological uncertainties in models and the examination of species-environment relationships. <img height="20" src="img/R.png" alt="R">
- [SpThin](https://github.com/mlammens/spThin) - Functions for Spatial Thinning of Species Occurrence Records for
Use in Ecological Models. <img height="20" src="img/R.png" alt="R">

## Spatial autocorrelaton

- [spdep](https://github.com/r-spatial/spdep/) - Creates spatial weights matrix objects from polygon contiguities, from point patterns by distance and tessellations, for summarizing these objects, and for permitting their use in spatial data analysis, including regional aggregation by minimum spanning tree. <img height="20" src="img/R.png" alt="R">
- [ncf](https://github.com/objornstad/ncf) - R functions for analyzing spatial (cross-)covariance: the nonparametric (cross-)covariance function, the spline correlogram, the nonparametric phase coherence function, local indicators of spatial association (LISA), (Mantel) correlogram, (Partial) Mantel test. <img height="20" src="img/R.png" alt="R">
- [esda](https://github.com/pysal/esda) - Methods for testing for global and local autocorrelation in areal unit data. <img height="20" src="img/python.png" alt="Pytnon">
- [blockCV](https://github.com/rvalavi/blockCV) - Package creates spatially or environmentally separated training and testing folds for cross-validation to provide a robust error estimation in spatially structured environments. <img height="20" src="img/R.png" alt="R">

## Uncertainty quantification

- [inlabru](https://github.com/inlabru-org/inlabru/) - Packege to facilitate spatial modeling using integrated nested Laplace approximation via the R-INLA package. <img height="20" src="img/R.png" alt="R">
- [Vizumap](https://github.com/lydialucchesi/Vizumap) - Package for visualizing uncertainty in spatial data. <img height="20" src="img/R.png" alt="R">
- [spup](https://cran.r-project.org/web/packages/spup/index.html) - Uncertainty propagation analysis in spatial environmental modelling. <img height="20" src="img/R.png" alt="R"> [[paper](https://journal.r-project.org/archive/2018/RJ-2018-047/RJ-2018-047.pdf)]
- [uncertainty-toolbox](https://github.com/uncertainty-toolbox/uncertainty-toolbox) - a Python toolbox for predictive uncertainty quantification, calibration, metrics, and visualization. <img height="20" src="img/python.png" alt="python"> [[paper](https://arxiv.org/abs/2109.10254)] 

## Modeling

- [sdmTMB](https://github.com/pbs-assess/sdmTMB/) - R package that fits spatial and spatiotemporal GLMMs (Generalized Linear Mixed Effects Models) using Template Model Builder, R-INLA, and Gaussian Markov random fields. <img height="20" src="img/R.png" alt="R">
- [verde](https://github.com/fatiando/verde) - Python library for processing spatial data (bathymetry, geophysics surveys, etc) and interpolating it on regular grids (i.e., gridding). <img height="20" src="img/python.png" alt="Python">
- [GSTools](https://github.com/GeoStat-Framework/GSTools) - Geostatistical toolbox: random fields, variogram estimation, covariance models, kriging and much more. <img height="20" src="img/python.png" alt="Python">
- [Whitebox](http://www.uoguelph.ca/~hydrogeo/Whitebox/) - An open source desktop GIS and remote sensing software package for general applications of geospatial analysis and data visualization. <img height="20" src="img/rust.png" alt="Rust">
- [Google Earth Engine](https://earthengine.google.com/) - Combines a multi-petabyte catalog of satellite imagery and geospatial datasets with planetary-scale analysis capabilities. Scientists, researchers, and developers use Earth Engine to detect changes, map trends, and quantify differences on the Earth's surface. <img height="20" src="img/gee.png" alt="Rust">
- [GeoStats.jl](https://github.com/JuliaEarth/GeoStats.jl) - An extensible framework for geospatial data science and geostatistical modeling fully written in Julia. <img height="20" src="img/julia.png" alt="Julia">
- [torchgeo](https://github.com/microsoft/torchgeo) - datasets, samplers, transforms, and pre-trained models for geospatial data. <img height="20" src="img/pytorch.png" alt="Torch">
  
## Reference

>1. [Awesome-Geospatial](https://github.com/sacridini/Awesome-Geospatial) - geospatial analysis tools.
>2. [Awesome-GIS](https://github.com/mishagrol/Awesome-Environmental-Geospatial) - collection of geospatial related sources, including cartographic tools, geoanalysis tools, developer tools, data, conference & communities, news, massive open online course, some amazing map sites, and more.
>3. [Change-Detection-Review](https://github.com/MinZHANG-WHU/Change-Detection-Review) - collection of methods, applications, and challenges of AI for change detection.
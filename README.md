# Jupyter notebook tutorials for the Copernicus Climate Change and Atmosphere Monitoring Services

This repository hosts Jupyter notebook training material for the [Copernicus Climate Change Service (C3S)](https://climate.copernicus.eu/) and the [Copernicus Atmosphere Monitoring Service (CAMS)](https://atmosphere.copernicus.eu/). 

The tutorials are designed for anyone interested in using C3S & CAMS data and has the following objectives:
* to demonstrate how data can be accessed via the [Climate Data Store (CDS)](https://cds.climate.copernicus.eu/cdsapp#!/home) and the [Atmosphere Data Store (ADS)](https://ads.atmosphere.copernicus.eu/#!/home), and
* to offer `example applications` and `analysis workflows` for different data types


## How to use these tutorials
These tutorials are in the form of [Jupyter notebooks](https://jupyter.org/). You will not need to install any software as there are a number of free cloud-based services to create, edit, run and export Jupyter notebooks. Here are some examples:

|Binder|Kaggle|Colab|Nbviewer|
|:-:|:-:|:-:|:-:|
|[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/)|[![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code)|[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)|[![NBViewer](https://raw.githubusercontent.com/ecmwf-projects/copernicus-training/master/img/nbviewer_badge.svg)](https://nbviewer.org/)|
|Binder may take some time to load the notebooks, so please be patient!|Before you can run the notebooks in Kaggle, you will need to login/register, and switch on the internet via *settings*|You will need a Google account to run the notebooks in Google Colab. Some packages may need to be installed using the command `!pip install (package name)`|Nbviewer will not run the notebooks, only render them|

If you would like to run the notebooks in your own environment, we suggest you install [Anaconda](https://docs.anaconda.com/anaconda/install/), which contains most of the libraries you will need. You will also need to install [Xarray](http://xarray.pydata.org/en/stable/) for working with multidimensional data in netcdf files, and the CDS/ADS API (`pip install cdsapi`) for downloading data programatically from the CDS & ADS.

This training material is made freely available on the [ecmwf-projects](https://github.com/ecmwf-projects) Github space under a [Apache 2.0 license](./LICENSE).


## Tutorials on C3S data

#### Introduction to the Climate Data Store (CDS)
* [C3S Climate Data Store - Introduction](https://nbviewer.jupyter.org/github/ecmwf-projects/copernicus-training/blob/master/C3S_climate-data-store.ipynb)

#### Analysis examples - Climate reanalysis data
* [C3S Climate reanalysis - Tutorial on analysis of climatologies and trends in ERA5 climate reanalysis data](https://nbviewer.jupyter.org/github/ecmwf-projects/copernicus-training/blob/master/C3S_climatology.ipynb)
* [C3S Climate reanalysis - Analysis of the September 2020 European heatwave using C3S reanalysis data](https://nbviewer.jupyter.org/github/ecmwf-projects/copernicus-training/blob/master/C3S_heatwave-analysis.ipynb)
* [C3S Climate reanalysis - Tutorial on calculating a climate index for wind chill](https://nbviewer.jupyter.org/github/ecmwf-projects/copernicus-training/blob/master/C3S_climate-indices.ipynb)
* [C3S Climate reanalysis - Tutorial sull'uso dei dati del C3S (*in Italian*)](https://nbviewer.jupyter.org/github/ecmwf-projects/copernicus-training/blob/master/C3S_data-tutorial-italiano_2020-11.ipynb)

#### Analysis examples - Climate projections
* [C3S Climate projections - CMIP6 Global climate projections](https://nbviewer.jupyter.org/github/ecmwf-projects/copernicus-training/blob/master/C3S_CMIP6-climate-projections.ipynb)
* [C3S Climate projections - CORDEX Regional climate projections](https://nbviewer.jupyter.org/github/ecmwf-projects/copernicus-training/blob/master/C3S_CORDEX-regional-climate-projections.ipynb)


## Tutorials on CAMS data

#### Introduction to the Atmosphere Data Store
* [CAMS Atmosphere Data Store - Introduction](https://nbviewer.jupyter.org/github/ecmwf-projects/copernicus-training/blob/master/CAMS_atmosphere-data-store.ipynb)

#### Application examples
* [CAMS Atmospheric Composition Data Access and Analysis Tutorial](https://nbviewer.jupyter.org/github/ecmwf-projects/copernicus-training/blob/master/CAMS_atmospheric-composition.ipynb)
* [CAMS dust monitoring](https://nbviewer.jupyter.org/github/ecmwf-projects/copernicus-training/blob/master/CAMS_dust-monitoring.ipynb)
* [CAMS wildfire emissions](https://nbviewer.jupyter.org/github/ecmwf-projects/copernicus-training/blob/master/CAMS_fire-monitoring.ipynb)
* [CAMS ozone monitoring](https://nbviewer.jupyter.org/github/ecmwf-projects/copernicus-training/blob/master/CAMS_ozone.ipynb)
* [CAMS global reanalysis (EAC4) monthly averaged fields](https://nbviewer.jupyter.org/github/ecmwf-projects/copernicus-training/blob/master/CAMS_global-reanalysis.ipynb)
* [CAMS cross-section plot of sulphur dioxide (SO<sub>2</sub>) for La Palma volcanic eruption in October 2021](https://nbviewer.jupyter.org/github/ecmwf-projects/copernicus-training/blob/master/CAMS_vertical-cross-section-volcanic-eruption.ipynb)
* [CAMS European air quality index (EAQI)](https://nbviewer.jupyter.org/github/ecmwf-projects/copernicus-training/blob/master/CAMS_European-air-quality-index.ipynb)


## Tutorials on both C3S and CAMS data
* [Tutorial on Copernicus ECMWF Data Access](https://nbviewer.jupyter.org/github/ecmwf-projects/copernicus-training/blob/master/Copernicus-ECMWF-data-tutorial_2021-02.ipynb)

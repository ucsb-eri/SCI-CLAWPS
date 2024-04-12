---
layout: splash
title: "SCI-CLAWPS Tools"
permalink: /tools/
author_profile: false
header:
  overlay_color: "#5e616c"
  overlay_image: ./assets/images/Sac_Float4_025.jpg
excerpt: "Here is a list of tools developed by the research group."
---

## The STOchastic Rainstorm Model (STORM)
This is a decision-support tool created to simulate individual rainstorms over a basin or region at high temporal and spatial resolution. This parsimonious model enables simulation of stationary climate based on historical data, or climate change based on step changes and/or trends in key climate variables. STORM 1.0 can be downloaded from [GitHub](https://github.com/blissville71/STORM). The supporting documentation can be found below.

**Singer, M.B.**, Michaelides, K., Hobley, D.E.J. (2018); STORM 1.0: A simple, flexible, and parsimonious stochastic rainfall generator for simulating climate and climate change, _Geoscientific Model Development_, 11, 3713-3726, doi: [10.5194/gmd-11-3713-2018](https://www.geosci-model-dev.net/11/3713/2018/). [<span style="color:red">pdf</span>](https://www.geosci-model-dev.net/11/3713/2018/gmd-11-3713-2018.pdf)		
   
and the following paper provides an application of the model:

**Singer, M.B.**, Michaelides, K. (2017); Deciphering the expression of climate change within the Lower Colorado River basin by stochastic simulation of convective rainfall, _Environmental Research Letters_, 12:104011, doi: [10.1088/1748-9326/aa8e50](https://iopscience.iop.org/article/10.1088/1748-9326/aa8e50). [<span style="color:red">pdf</span>](https://iopscience.iop.org/article/10.1088/1748-9326/aa8e50/pdf) 

We are currently working on the next version of the model (STORM.v2), which will explicity capture the inherent relationships between rainfall intensity and duration, and it will include a front-end pre-processing code for creating input pdfs, as well as a PET calculator that accesses historical reanalysis climate data from ERA5. After that, we will be working on a regionalized version of the model as part of the [DOWN2EARTH](http://down2earthproject.org/) project. 

 
## The Inverse Barbour Model (ISO-Tool)
This tool is designed to enable users to characterize the oxygen isotopic ratio of source waters used by plants during distinct periods of growth. It employs an inversion of the Barbour model of isotopic fractionation within plants (building on Craig-Gordon theory) to convert a known oxygen isotope ratio in tree ring cellulose into the ratio of its source water, based on climatic and physiological input variables. The model includes a Monte Carlo method for characterizing the uncertainty in this back-calculated ratio. The tool is currently being reviewed for publication, but it can be downloaded from [GitHub](https://github.com/blissville71/InverseBarbourModel). The supporting documentation can be found in this paper:

*Sargeant, C.I., **Singer, M.B.**, Vallet-Coulomb, C. (2019); Identification of Source-water Oxygen isotopes in trees Toolkit (ISO-Tool) for deciphering historical water use by forest trees, _Water Resources Research_, doi: [10.1029/2018WR024519](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2018WR024519). [<span style="color:red">pdf</span>](../assets/pdfs/publications/Sargeant_etal_2019.pdf)


## Water Balance Model for Drylands (DRYP)
This model is designed to address major shortcomings in the linkages between climate and the water balance within dryland regions. Specifically, this model incorporates spatially and temporally varying rainfall (via STORM--see above), partitioning of runoff and infiltration, transmission losses in dryland channels, and diffuse and focused groundwater recharge. The first version of this tool, DRYP 1.0, has been published and can be downloaded from [GitHub](https://github.com/AndresQuichimbo/DRYP). We are currently working to create a regionalized version of DRYP as part of the [DOWN2EARTH](http://down2earthproject.org/) project.

*Quichimbo, E.A., **Singer, M.B.**, Michaelides, K., Hobley, D., Rosolem, R., Cuthbert, M.O. (2021). DRYP 1.0: A parsimonious hydrological model of DRYland Partitioning of the water balance, _Geoscientific Model Development_, doi:[10.5194/gmd-2021-137](https://gmd.copernicus.org/articles/14/6893/2021/). [<span style="color:red">pdf</span>](../assets/pdfs/publications/Quichimbo_etal_2021.pdf)


## Flow and Sediment Transport in Channel Cross Sections 
This simple code (in Excel and Matlab formats) is designed to make quick and straightforward calculations of flow and sediment transport in river channel cross sections. It can be used to develop synthetic stage discharge-rating curves or to estimate sediment movement for various hydrographs, or due to varying grain roughness, cross sectional shape, and/or river gradient.

**Coming soon**


## Streamflow Simulation Model (HYDROCARLO) 
This Matlab code simulates stochastic river flows through a network. The details and application to sediment transport and river rehabilitation can be found here:

**Singer, M.B.**, Dunne, T. (2004); An empirical-stochastic, event-based program for simulating inflow from a tributary network: Framework and application to the Sacramento River basin, California. _Water Resources Research_, 40, W07506, doi: [10.1029/2003WR002725](http://onlinelibrary.wiley.com/doi/10.1029/2003WR002725/abstract). [<span style="color:red">pdf</span>](../assets/pdfs/publications/Singer_Dunne_2004b.pdf) 

**Singer, M.B.**, Dunne, T. (2004); Modeling decadal bed-material sediment flux based on stochastic hydrology. _Water Resources Research_, 40, W03302, doi: [10.1029/2003WR002723](http://onlinelibrary.wiley.com/doi/10.1029/2003WR002723/abstract). [<span style="color:red">pdf</span>](../assets/pdfs/publications/Singer_Dunne_2004.pdf)	

**Singer, M.B.**, Dunne, T. (2006); Modeling the influence of river rehabilitation scenarios on bed material sediment flux in a large river over decadal timescales. _Water Resources Research_, 42, W12415, doi: [10.1029/2006WR004894](http://onlinelibrary.wiley.com/doi/10.1029/2006WR004894/full). [<span style="color:red">pdf</span>](../assets/pdfs/publications/Singer_Dunne_2006.pdf)


## Time Series Simulation Framework for Relating River Flow and Sediment Concentration 
This Matlab code estimates the relationships between sediment concentration in a river to the driving flow in a time series sense, capturing the time dependency in these relationships. The details can be found here: 

**Singer, M.B.**, Dunne, T.(2001); Identifying eroding and depositional reaches of valley by analysis of suspended-sediment transport in the Sacramento River, California. _Water Resources Research_, 37(12):3371-3382, doi: [10.1029/2001WR000457](http://onlinelibrary.wiley.com/doi/10.1029/2001WR000457/full). [<span style="color:red">pdf</span>](../assets/pdfs/publications/Singer_Dunne_2001.pdf)   

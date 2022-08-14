---
layout: archive
title: "Research Highlights"
permalink: /portfolio/
author_profile: true
---

Coupled Data Assimilation
---------------

Data assimilation, a method for combining real world data with dynamical models, is commonly used to set initial conditions for numerical weather prediction. I work on several projects in coupled data assimilation where there are two or more interacting model components, like atmosphere-ocean systems. In my PhD research I proposed a new way to treat model uncertainties in a coupled system. I created a multiscale extension of the commonly used Gaspari-Cohn localization function. In my current work I examine different practical localization methods for atmosphere-ocean systems with the aim of guiding NOAA’s development of a strongly coupled data assimilation system. I also work on assimilating soil moisture observations into NOAA’s coupled land-atmosphere model. 

Related publications: [Stanley et al., NPG (2021)](https://doi.org/10.5194/npg-28-565-2021)

Stochastic Parameterizations
---------------

The density of seawater is an important quantity in ocean models. There is an error in the way ocean models calculate density, which is especially pronounced in the ocean models used for climate forecasting. Using output from a high-resolution ocean model, I quantify this error in density and propose a correction. We do not expect to be able to perfectly parameterize this error as it is affected by turbulent and unpredictable fluctuations. Instead, I proposed a stochastic correction which replicates its statistical properties: mean, variance, and spatiotemporal correlation structure. Stochastic parameterizations, such as this one, help to model realistic spread in ensemble data assimilation systems. This correction to the equation of state is now implemented in NOAA’s MOM6 ocean model. 

Related publications: [Stanley et al., JAMES (2020)](https://doi.org/10.1029/2020MS002151); [Kenigson et al. (2022)](https://doi.org/10.1029/2021MS002844).

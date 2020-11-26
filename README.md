# Comparing remotely sensed observations of clouds and aerosols in the Southern Ocean with climate model simulations

This repository contains source files and accompanying analyses
of the doctoral thesis *Comparing remotely sensed observations of clouds and aerosols in the Southern Ocean with climate model simulations*.

**School:** University of Canterbury, Christchurch, New Zealand (submitted)\
**Date:** 30 May 2020\
**Supervisors:** Prof. Adrian McDonald, Dr. Olaf Morgenstern\
**Archive**: [Zenodo](https://zenodo.org/record/3865850)\
**DOI**: [10.5281/zenodo.3865850](https://doi.org/10.5281/zenodo.3865850)

## Abstract

Southern Ocean (SO) shortwave (SW) radiation biases are a common problem
 in contemporary general circulation models (GCMs), with most models 
exhibiting a tendency to absorb too much incoming SW radiation. These 
biases have been attributed to deficiencies in the representation of 
clouds during the austral summer months, either due to cloud cover or 
cloud albedo being too low. They affect simulation of New Zealand (NZ) 
and global climate in GCMs due to excessive heating of the sea surface 
and the effect on large-scale circulation. Therefore, improvement of 
GCMs is necessary for accurate prediction of future NZ and global 
climate. Currently the New Zealand Earth System Model (NZESM), based on 
the UK Hadley Centre Coupled Model version 3 (HadGEM3), is developed at 
the National Institute of Water and Atmospheric Research (NIWA) and the 
University of Canterbury. We performed ship-based lidar, radar, 
radiosonde and weather observations on two SO voyages and processed data
 from multiple past SO voyages. We used the observations and satellite 
measurements for evaluation of NZESM and contrasting with the Modern-Era
 Retrospective analysis for Research and Applications version 2 
(MERRA-2) to better understand the source of the problem. Due to the 
nature of lidar observations (the laser signal is quickly attenuated by 
clouds) they cannot be used for 1:1 comparison with a model without 
using a lidar simulator, which performs atmospheric radiative transfer 
calculations of the laser signal. We modify an existing satellite lidar 
simulator present in the Cloud Feedback Model Intercomparison Project 
(CFMIP) Observational Simulator Package (COSP) for use with the 
ground-based lidars used in our observations by modifying the geometry 
of the radiative transfer calculations, Mie and Rayleigh scattering of 
the laser signal. We document and make the modified lidar simulator 
available to the scientific community as part of a newly-developed lidar
 processing tool called the Automatic Lidar and Ceilometer Framework 
(ALCF), which enables unbiased comparison between lidar observations and
 models by performing calibration of lidar backscatter, noise removal 
and consistent cloud detection. We apply the lidar simulator on NZESM 
model fields. Significant SW radiation errors in the SO of up to 21 Wm<sup>-2</sup>
 are shown to be present in the model. Using the lidar observations, we 
find that the model underestimates overall cloud cover by about 9% and 
strongly underestimates boundary layer low-level stratocumulus (Sc) 
cloud below 1 km and fog. By using radiosonde observations, we find that
 the observed cloud was strongly linked to the boundary layer stability 
and sea surface temperature, while this relationship is weaker in the 
model. We identify that these errors are not due to misrepresentation of
 large-scale circulation, which is prescribed in our model based on 
global satellite observations by nudging. We conclude that the problem 
is likely in the subgrid-scale parametrisation schemes of the boundary 
layer, convection and large-scale could. In order to address the 
deficiencies identified we perform experimental simulations of NZESM 
with modifications of the parametrisation schemes. We find that a 
three-layer cloud profiles were common in the Ross Sea region, 
consisting of cumulus (Cu) below Sc, and corresponding to local 
thermodynamic levels: lifting condensation level, dry and moist neutral 
buoyancy levels of parcels lifted from the surface. We find that not 
enough moisture is transported to the top of the boundary layer to form 
Sc clouds. By increasing surface moisture flux and convective mass flux 
in the model we improve the Sc cloud simulation, but we show that a lack
 of vertical moisture transport across the lifting condensation level 
from the surface layer to the zone of convective mass flux is a likely 
limiting factor. We show that the modifications had a positive impact on
 the Southern Ocean and global radiation balance of up to 5 Wm<sup>-2</sup>
 in zonal average over this limited time period. We suggest that further
 research should focus on the weak vertical coupling between the 
boundary layer turbulence and boundary layer convection parametrisation 
in the model, and that the lidar simulator framework is used as a cloud 
evaluation tool in further studies due to its benefits over more 
statistical approaches, which tend to hide compensating biases.

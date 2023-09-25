# Evidence for kilometer-scale biophysical features at the Gulf Stream front

Authors: Patrick Clifton Gray, Ivan Savelyev, Nicolas Cassar, Marina Levy, Emmanuel Boss, Yoav Lehahn, Guillaume Bourdin, Kate A. Thompson, Anna Windle, Jessica Gronniger, Sheri Floge, Dana E. Hunt, Greg Silsbe, Zackary I. Johnson, David W. Johnston

This work is currently available on bioRxiv at: [link TBD] and is under review at the Journal of Geophysical Research: Oceans.

### Running the Notebook
Once you have pulled the repo down locally via git and have Docker installed all code here can be run fully in Docker based on a prebuilt environment by running:

`docker run -it -v <location of code>:/home/jovyan --rm -p 8888:8888 pangeo/pangeo-notebook:2021.05.15 jupyter lab --ip 0.0.0.0`

This will launch a Jupyter Lab instance that can run everything for you. This can also be easily done in the cloud if you have a cloud environment that can be launched with a Docker image.

## Plain Language Summary of this Work

Phytoplankton move with large currents and are stirred by eddies with diameters ranging from 100s of kilometers down to the meter scale. Their growth is impacted by physical factors like light and temperature and also chemical and biological factors like nutrient availability, and their accumulation is also impacted by top down controls (zooplankton grazing, viral lysis) and competition with other phytoplankton. This interplay of physics and biology in determining the biomass and composition of phytoplankton communities is poorly understood and is key to understanding marine ecosystem resilience and structure in a changing ocean. In this work we investigated the impact of physics and biology on phytoplankton across scales focusing on the Gulf Stream front. Fronts in the ocean are where lines of equal density go from being horizontal to having a vertical tile, and because of this can enable nutrients and plankton to move from depth to the surface and vice versa. The objective of this work is to understand how physics might drive important changes in phytoplankton biomass and composition in the Gulf Stream front, which is amongst the sharpest gradients in temperature, density, and current speed in the global ocean. We find two frequent processes at the front, the apparent subduction of cold filaments down along the edge of the Gulf Stream, associated with meander troughs, and obduction of high salinity Sargasso Sea water into the front linked to meander crests. While ephemeral, these processes are frequent and could have a large impact on local phytoplankton biomass, phytoplankton composition, and the export of organic matter to depth.

### The key points of this work are:
-  The frontal zone between the Gulf Stream and the shelf has an interface water mass which appears to have different origins with a range of biogeochemical impacts.
-  Meanders appear to largely control the frontal interface: troughs lead to subduction of shelf filaments and crests lead to obduction of high salinity water. 
-  These two processes are common at the front and could lead to ephemeral kilometer-scale export and productivity.

### Notebooks
There are a number of notebooks that can be used to recreate this analysis along with the provided data: 
- In primary_analysis.ipynb we do most of the work which analyzes all and combines nearly all the primary datasets and then visualizes all the transects and generates the supplemental figures.
- In analyzing_aug_cruise.ipynb, analyzing_sept_cruise.ipynb, and analyzing_march_cruise.ipynb the individual crusie data from those three periods is visualized and the phytoplankton community composition figures are created.
- In seasonality_analysis.ipynb the data is pulled in for the large scale analysis of seasonality on either side of the front in T and chl a.

### Citation
DOI TBD

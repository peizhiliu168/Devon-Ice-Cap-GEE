# Utilizing Google Earth Engine to Retrieve the Devon Ice Cap’s Equilibrium Line Altitude​

<p align="center"> <img src="readme_images/map.png" width="300"> <img src="readme_images/flowchart.jpg" width="300"> </p>

<p align="center"><img src="readme_images/ela_image.png" width="200"> <img src="readme_images/kmeans_image.png" width="200"> <img src="readme_images/ELA_GRAPH.png" width="200"></p>

## Description
This project took place from Summer 2018 - Spring 2019 and was a collaboration between:
* Peizhi Liu (Troy High School)
* Kevin Zhou (Troy High School)
* Dr. Grant Gunn (Assistant Professor in the Department of Geography, Environment, and Spatial Sciences at Michigan State University)  

The goal of this project was to estimate glacial melt of the Devon Ice Cap by tracking its equilibrium line altitude with Google Earth Engine and machine learning.  Sentinel-1 satellite imagery was processed and cluster using Google Earth Engine, with additional processing and analysis completed with QGIS and Python scripts.
Additional project details can be found within this GitHub repository.

## Abstract
Glaciers have exhibited increased melting rates due to rising global temperatures resulting from climate change. To track the effects of climate change on glacial mass balance, the equilibrium line altitude (ELA), the height at which snow accumulation equals snow ablation (mass loss), is commonly used. However, determining a glacier’s ELA via prior methods has been cumbersome due to limited satellite imagery and large amounts of data processing. Google Earth Engine (GEE) bypasses these issues, granting users free access to petabytes of regularly updated, pre-processed satellite imagery without tedious data download. We propose utilizing GEE as a novel approach to determine a glacier’s ELA and extent of melt, observing the Devon Ice Cap from 2015-2018 as a case study. We used satellite data from various satellites (Sentinel-1, Landsat 8, etc.) and GEE’s built-in classification algorithm functions to cluster the ice cap into regions of differing melt levels. By doing this, we were able to obtain the Devon Ice Cap’s ELA values each year, which were consistent with past in-situ measurements. Using the melt clusters to generate accumulation and ablation zones, we were then able to estimate the extent of glacial melt of the ice cap as a percentage. Currently, satellites like Sentinel-1 only being operational for a few years limits our ability to establish long-term trends. However, as more data is accrued over time, GEE’s efficacy in tracking glacial change will only grow, making our methodology essential to properly monitor the effects of climate change on Earth.

## Recogition
This project received the following awards: 
* Intel International Science and Engineering Fair (ISEF) 2019 finalist
* Science and Engineering Fair of Metropolitan Detroit (SEFMD) Grand Award
* American Meteorological Society (AMS) Certificate of Outstanding Achievement

Additionally, an interview with Michigan State University's WKAR Public Media can be found here: <a href="https://www.wkar.org/post/msu-professor-and-troy-high-school-students-collaboration-leads-award-winning-climate-research#stream/0">MSU Interview<a>



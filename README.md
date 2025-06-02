# Using K-means unsupervised learning to track forest cover loss in Borneo.

## Table of Contents
- [Overview](#overview)
- [Methodology](#methodology)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [References](#references)

## Background 
This project is a submission for the module Artificial Intelligence for Earth Observation, forming part of my education on the AI for Sustainable Development MSc at University College London.

Deforestation is a major contributing factor to the current ecological crisis facing the planet. Some areas have suffered its effects more acutely than others - the tropics lost a record-shattering 6.7 million hectares of primary rainforest in 2024, an area almost the size of Panama [1]. Borneo was chosen for this study, as its a region located in the tropics home to a diverse ecosystems and animals such as the orangutan, pygmy elephant and clouded leopard. It has only half of its forest cover remaining today, down from 75% in the 1980s [2]. A primary driver for deforestation in this region is the expansion of palm oil plantations for agriculture, industrial palm plantations grew by 128,000 hectares in 2023, a 59% increase from the previous year, the associated deforestation increased by 53% [3]. This study aims to highlight an issue facing tropical ecosystems across the world, an issue where economic productivity is prioritised over the preservation of rich biodiversity.

## Overview
Remote sensing is the process of gathering information about a region of interest from a distance, the use of satellite imagery allows for the implementation of machine learning techniques to track deforestation in a much more cost and time efficient manner.To understand what the deforestation picture looks like in Borneo, we utilise remote sensing by analysing images from the satellite Sentinel-2.  The images from this satellite were chosen as it contains the required spectral bands for vegetation analysis, with NIR (Near InfraRed) and red bands essential for NDVI calculation. Due to the various indices calculation


Copernicus browser + GEE, opted for GEE directly through the notebook 

Brief description of the problem and your approach

## Methodology

Description about the indices


![K-means Clustering Methodology](borneo_kmeans_diagram.png)



## Installation
```bash
# Clone the repository
git clone https://github.com/your-username/your-repo.git

# Install dependencies
pip install -r requirements.txt


## References 
[1] - https://gfr.wri.org/latest-analysis-deforestation-trends
[2] - https://www.unep.org/news-and-stories/story/deforestation-borneo-slowing-regulation-remains-key
[3] -

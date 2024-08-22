---
permalink: /research/
author_profile: false
type: page
classes: wide2
layout: single
title: "Research"
header:
    overlay_image: /assets/images/header_photo_small.jpg
    caption: Greak Smoky National Park

feature_row1:
  - image_path: assets/images/CEDAR-GPP_video.gif
    title: "Terrestrial ecosystem carbon and water dynamics"
    excerpt: >
        Terrestrial ecosystems continuously exchange carbon, water, and energy with the atmosphere, processes that are fundamental to ecosystem functioning and crucial for regulating Earth’s climate. For instance, in recent decades, ecosystems have removed one-third of anthropogenic carbon emissions, partly mitigating climate change. Despite the importance, quantitatively understanding ecosystem carbon and water dynamics, especially in response to environmental and climatic changes, remains a significant challenge. This is due to the intrinsic complexity of these processes and a lack of direct observations at scale. We develop novel frameworks to robustly quantify ecosystem carbon and water dynamics, by integrating ground-based measurements (e.g. eddy covariance), satellite remote sensing, and advanced machine/deep learning. We answer fundamental questions on how ecosystem functions and services are changing, improving our predictive understanding of the Earth system. <br />
        <br />
        **Key results**: <br />
        - CEDAR-GPP: a novel data-driven GPP dataset that comprehensively represent CO2 fertilization effect on global photosynthesis. **Kang, Y.**,  et al., 2024, ESSD [preprint](https://doi.org/10.5194/essd-2023-337)   <br />
        - Evaluating automated Machine Learning for quantifying ecosystem productivities. Gaber, M., **Kang, Y.** et al Biogeosciences, 2024. [paper](https://doi.org/10.5194/bg-21-2447-2024)  <br />
        - A Transformer-based predictor of ecosystem photosynthesis dynamics:  Nakagawa, R., ... **Kang, Y.** (2023). CVPR MultiEarth Workshop. [preprint](https://arxiv.org/pdf/2306.13815.pdf)

feature_row2:
  - image_path: assets/images/LAI_StockSnap_OOP3TR13DA.jpg
    title: "Quantifying vegetation structural dynamics"
    excerpt: >
        Leaf area index (LAI) is a structural biophysical variable describing the amount leaves that plant canopies have. Robust estimation of LAI is critical understand carbon, water, and enbergy exchange between plant, soil, atmosphere. I use statistical and machine learning approaches to quantify LAI from local to global scales at high (decametric) spatial resolutions and evaluate how uncertainties in LAI estimation impact the modeling of water fluxes. <br />
        <br />
        **Kang, Y.**, Ozdogan, M., Gao, F., et al. (2021). A data-driven approach to estimate leaf area index for Landsat images over the contiguous US. Remote Sensing of Environment, 258, 112383. [link](https://doi.org/10.1016/j.rse.2021.112383)  <br />
        **Kang, Y.**, Gao, F., Anderson, M. et al. Evaluation of satellite Leaf Area Index in California vineyards for improving water use estimation. Irrig Sci (2022). [link](https://doi.org/10.1007/s00271-022-00798-8) <br />
        **Kang, Y.**, Özdoğan, M., Zipper, S. C., et al. (2016). How universal is the relationship between remotely sensed vegetation indices and crop leaf area index? A global assessment. Remote Sensing, 8(7), 597. [link](https://doi.org/10.3390/rs8070597)  <br />
        Marshall, M., Okuto, E., **Kang, Y.**, et al. (2016). Global assessment of Vegetation Index and Phenology Lab (VIP) and Global Inventory Modeling and Mapping Studies (GIMMS) version 3 products. Biogeosciences, 13(3), 625–639. [link](https://doi.org/10.5194/bg-13-625-2016)      
    url: https://github.com/yanghuikang/Landsat-LAI
    btn_label: "Landsat-LAI GEE code"
    btn_class: "btn--primary"

feature_row3:
  - image_path: assets/images/crop_irrigation.jpg
    title: "Forecasting crop yields"
    excerpt: >
        Robust and timely estimations of crop yields in a spatially explicit manner provide essential information to farmers, private partners, and policy-makers. I employ both machine learning and crop growth modeling approaches to improve the accuracy and reliability of crop yield estimations across spatial scales over large areas.  For example, I developed a hierarchical data assimilation framework to combine mechanistic crop modeling and satellite observations to estimate crop yield at individual field levels in the Midwest US. I also explored the strength of novel machine/deep learning algorithms to provide a timely forecast of yields at county levels. <br /> 
        <br /> 
        **Kang, Y.**, & Özdoğan, M. (2019). Field-level crop yield mapping with Landsat using a hierarchical data assimilation approach. *Remote Sensing of Environment*, *228*, 144–163. [link](https://doi.org/10.1016/j.rse.2019.04.005) <br />
        **Kang, Y.**, Ozdogan, M., Zhu, X., Ye, Z., Hain, C., & Anderson, M. (2020). Comparative assessment of environmental variables and machine learning algorithms for maize yield prediction in the US Midwest. *Environmental Research Letters*, *15*(6). [link](https://doi.org/10.1088/1748-9326/ab7df9) <br/> 
        Yuchi, M., Zhang, Z., **Kang, Y.**, & Ozdogan, M. (2021). Corn yield prediction and uncertainty analysis based on remotely sensed variables using a Bayesian neural network approach. *Remote Sensing of Environment*, *258*, 112408. [link](https://doi.org/10.1016/j.rse.2021.112408)    
---

## Research Projects

{% include feature_row id="feature_row1" type="left" %}  
{% include feature_row id="feature_row2" type="left" %}  
{% include feature_row id="feature_row3" type="left" %}

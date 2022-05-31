# Overview

Predicting urban events such as transportation resource demand, traffic accidents, and traffic volumes relies on spatio-temporal neural methods. Existing approaches frequently use a common set of urban features (typically held by government agencies) such as road network and weather. Even as data is increasingly available through open data portals, identifying which datasets will improve a model amounts to trial and error, preparing the relevant datasets for use in neural models requires substantial effort, not all relevant datasets are available publicly due to privacy and administrative limitations, and training separate models for each task is expensive and redundant. We explore a different approach in which common set of integrated features learned across all relevant datasets can be pre-trained as a single data representation and reused across many tasks. At the same time, we remove the effects of sensitive attributes (i.e., race, income) from the pre-trained representation. Government agencies can periodically release an EquiTensor that encodes the dynamic features of the city to be used directly to improve prediction tasks. These features can provide better utility for city data, complementing “raw” access through open data portals, and potentially provide a single point of control for privacy and bias management. To this end, we propose a neural architecture to integrate a significant number of urban datasets into a learned spatiotemporal tensor, analogous to the role of pre-trained word vectors for NLP applications.

# Getting Started

This repository includes the code used for the experiments in EquiTensors: Learning Fair Integrations of Heterogeneous Urban Data, An Yan and Bill Howe, SIGMOD 2021.

# Publications

* [EquiTensors: Learning Fair Integrations of Heterogeneous Urban Data](https://dl.acm.org/doi/abs/10.1145/3448016.3452777), An Yan and Bill Howe, SIGMOD 2021
* [Fairness-Aware Demand Prediction for New Mobility](https://www.aaai.org/ojs/index.php/AAAI/article/view/5458), An Yan, Bill Howe, AAAI 2020
* [FairST: Equitable Spatial and Temporal Demand Prediction for New Mobility Systems](https://dl.acm.org/doi/10.1145/3347146.3359380), An Yan, Bill Howe, SIGSPATIAL 2019 (short paper)
* [Fairness in Practice: A Survey on Equity in Urban Mobility](http://sites.computer.org/debull/A19sept/A19SEPT-CD.pdf#page=51), An Yan, Bill Howe, Data Engineering (September 2019)

# Project Webpage

https://citytensors.github.io/citytensors/


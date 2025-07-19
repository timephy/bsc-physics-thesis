# bsc-physics-thesis

My bachelor's thesis of physics at [TUM](https://www.tum.de). The final submission is available as the [thesis.pdf](https://github.com/timephy/bsc-physics-thesis/blob/main/thesis.pdf) file in this repo.

## Improving the Neutrino Oscillation Sensitivity of IceCube with Graph Neural Networks

I wrote my thesis about improving the performance of a [graph neural network](https://en.wikipedia.org/wiki/Graph_neural_network) which is used by [IceCube](https://en.wikipedia.org/wiki/IceCube_Neutrino_Observatory), a [neutrino](https://en.wikipedia.org/wiki/Neutrino) telescope in Antarctica.

### Introduction

The IceCube Neutrino Observatory is the largest neutrino experiment ever constructed. It consists of over 5000 light-detecting digital optical modules (DOMs), which are buried in a volume of over 1 km³ in the ice of Antarctica. Such an experiment with as many individual detectors naturally yields tons of raw data, hence manual interpretation/analysis is not appropriate. [...] In this thesis, an effort is made to feed additional data to the network, which describes the local properties of the ice, to help the network understand the data context better. By also focusing the network’s attention on energies most relevant to neutrino oscillations, its performance will be increased in predicting the values necessary to build a mathematical model of neutrino oscillations.

### GraphNeT

GraphNeT is an open-source Python framework aimed at providing high quality, user friendly, end-to-end functionality to perform reconstruction tasks at neutrino telescopes using deep learning (DL). GraphNeT makes it fast and easy to train complex models that can provide event reconstruction with state-of-the-art performance, for arbitrary detector configurations, with inference times that are orders of magnitude faster than traditional reconstruction techniques.

- The neural network itself is available in the [GraphNeT repo](https://github.com/graphnet-team/graphnet)
- You can find my analyses inside the seperate [analyses repo](https://github.com/graphnet-team/analyses)

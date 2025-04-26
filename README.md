# Goku-ELG

[![Under Development](https://img.shields.io/badge/status-under--development-orange)](https://github.com/)
[![Built with GPflow](https://img.shields.io/badge/built%20with-GPflow-2ea44f)](https://gpflow.github.io/)
[![arXiv Preprint Coming Soon](https://img.shields.io/badge/arXiv-preprint%20coming%20soon-blue)](https://arxiv.org/)

A cosmological emulator for emission-line galaxies (ELGs), built using the GOKU simulation suite.

**Qezlou et al., in preparation**

---

## TL;DR

We use machine learning techniques to map from cosmological parameters to emission-line galaxy observables.

---

## What's New?

Resolving emission-line galaxies in N-body simulations requires high resolution, while achieving high-fidelity clustering statistics demands large volumes. We address both challenges **efficiently** by using machine learning models trained on the GOKU simulation suite [Yang et al. (2025)](https://ui.adsabs.harvard.edu/abs/2025PhRvD.111h3529Y/abstract).

Our method employs a **multi-fidelity Gaussian Process model** [Kennedy & O'Hagan (2000)](https://academic.oup.com/biomet/article-abstract/87/1/1/221217?redirectedFrom=PDF), [Ho et al. (2021)](https://arxiv.org/abs/2105.01081), along with elements of the [`Stochastic Variational GP`](https://arxiv.org/pdf/1411.2005) framework, extended to support datasets with varying uncertainty levels through a modified likelihood.

---

## Citation

Please cite the upcoming manuscript when using this code:

Qezlou et al., Goku-ELG: A Cosmological Emulator for Emission-Line Galaxies, in preparation (2025).
---

## License

© 2025 Qezlou, Yanhui Yang, Simeon Bird and Ming-Feng Ho. All rights reserved.  
License terms will be provided upon publication.

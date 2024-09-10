# MINAL Demo

This repository contains codes and simulations for our paper: **Multi-source Stable Importance Measure via Adversarial Machine Learning (MIMAL)**. Since some of the codes will be published in an `R`-package, we are currently only able to upload a demo Jupyter notebook showcasing the use of Gradient-Descent-Ascent (GDA) for minimax/maximin adversarial learning. The objective is to learn a minimax/maximin logistic regression for three sites against a sample-mean null model. Our observation is that the learning process at saddle points is faster and more stable than an empirical risk minimization procedure.

The Jupyter notebook file is called `GDA demo.ipynb`.

## Environment Setup

To run this notebook, you will need the following package versions:

- `torch`: 2.3.0
- `numpy`: 1.25.2

Ensure that you have these or compatible versions installed in your environment.

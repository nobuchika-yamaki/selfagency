README
Overview

This repository contains the full simulation code used to analyze agency attribution in asymmetric and symmetric predictive architectures. All results reported in the manuscript are reproducible from the provided code.

Requirements

Python ≥ 3.9

NumPy

Files

simulation.py
Main script implementing the generative process, predictive models, agency index, delay sweep, and robustness analyses.

How to run

Execute the script directly:

python simulation.py


The script runs all simulations with fixed random seeds and outputs internal variables used for analysis (agency index, critical delay, robustness results).

Reproducibility

All random processes use a fixed seed.

Identical input sequences are used across conditions.

No external data or pretrained models are required.

Output

The script computes:

Time series of agency index A(t)

Mean agency index across conditions

Critical delay τ_c

Effects of motor noise on agency attribution

No post-processing or manual intervention is required.

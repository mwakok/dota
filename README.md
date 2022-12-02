# Dose calculation via Transformers #

This repository contains the code to calculate the dose deposited by a mono-energetic beam of protons, for arbitrary patient geometries and beam energies. 

* GNU General Public License 3.0
* Copyright: Oscar Pastor-Serrano, TU Delft

### Credits ###

If you like this repository, please click on Star!

If you use the code for your research, please consider citing:

Pastor-Serrano, O., & Perkó, Z. (2021). Learning the Physics of Particle Transport via Transformers.
<https://arxiv.org/abs/2109.03951>

Pastor-Serrano, O., & Perkó, Z. (2022). Millisecond speed deep learning based proton dose calculation with Monte Carlo accuracy.
<https://doi.org/10.1088/1361-6560/ac692e>

This project is supported by the following institutions:

* KWF Kanker Bestrijding
* Department of Radiation Science and Technology (TU Delft)

### Requirements ###

* Tensorflow 2.5 or higher
* pymedphys
* tensorflow-addons


It is preferred to create a Conda environment to install these dependencies:
```
conda install mamba -n base -c conda-forge -y
mamba env create --file environment.yml
conda activate dota_env
```
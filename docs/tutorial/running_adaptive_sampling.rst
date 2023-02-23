Running Adaptive Sampling
=========================

With all of the files needed, running adaptive sampling is as simple as executing a python script!

Example scripts can be found in `fast/example_scripts/`

Currently, there are two example scripts:
1. FAST-RMSD simulations run on a local work-station by minimizing RMSD between two structures.
2. FAST-Distance simulations run on an HPC with LSF by maximizing distances between pairs of atoms.

Adaptive sampling has a lot of moving parts, so an attempt has been made to make this code modular and independent (for customizations and methods development).


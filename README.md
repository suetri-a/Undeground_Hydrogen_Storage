# Subsurface Hydrogen Storage Benchmark Study

This repository contains information and data related to a benchmark study on subsurface hydrogen storage. With the increasing interest in hydrogen as an energy source, geological porous formations offer a promising solution for hydrogen storage. Accurate numerical simulation is required to predict storage efficiency and effects. Through a series of test problems of increasing complexity related to subsurface hydrogen storage, we compared the performance of five simulators:

- ECLIPSE 100 *
- ECLIPSE 300 *
- GEM **
- ADGPRS
- OPM Flow

# Problems

## Problem #1: Molecular Diffusion in a One-Dimensional Column
This problem investigates gas mixing by molecular diffusion and advection in a 100 m, one-dimensional, vertical column with no flow boundaries. The column consists of hydrogen and methane, with hydrogen initially occupying the top half of the column. This results in a stably-stratified column, where mixing at the gas interface is driven primarily by diffusion.

## Problem #2: Gas Mixing in a Two-Dimensional Column

The second problem is an extension of Problem #1, but also includes the effects of gravity. For this problem, a 100-meter by 100-meter vertical section is applied, with methane and hydrogen initialized side by side. In addition to diffusion and advection, gravity effects play a role in the mixing because the heavier methane flows downward, and hydrogen flows upwards.

## Problem #3: Two-Phase Flow of Hydrogen and Water in a Radial Reservoir
The third problem investigates two-phase flow of hydrogen and water for a simplified storage reservoir geometry. Injection is made at a constant mass rate and flow is assumed to be two-dimensional and radial (line source). The reservoir is sealed at the top and bottom boundaries.

## Problem #4: Cyclic Hydrogen Storage in Anticlinal Structure

The final problem investigates cyclic hydrogen storage in an initially water-saturated porous formation, including storage build-up and shut-in phases. Storage containment is provided by an anticlinal trap structure, while hydrogen is injected and withdrawn using one vertical fully perforating well located at the top of the anticline structure.


## Results
The intercomparison of the five numerical simulators demonstrates a good quantitative agreement of predicted molar fractions, saturations or phase pressures, with only subtle differences arising due to the details of fluid properties and numerical discretization approaches. This intercomparison builds confidence in numerical simulation and provides a basis for more complex scenarios studies.

## Repository Contents

- `datasets/`: data used in the study
- `results/`: simulation results
- `scripts/`: scripts used in the study
- `LICENSE`: repository license
- `README.md`: repository information

<sub>* Mark of Slb (Schlumberger)</sub>

<sub>** Mark of CMG (Computer Modelling Group)</sub>


## License
This repository is licensed under the [MIT license](https://github.com/fgasa/Underground_Hydrogen_Storage/blob/main/LICENSE). You are free to use, copy, modify, however, the license comes with no warranty or liability and you must include a copy of the license. 
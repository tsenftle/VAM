# DFT Calculation Dataset

### Repository Description
This repository contains the density functional theory calculations used in the study. Each molecular species has an individual folder that includes geometry optimization, frequency analysis, and single-point energy calculations. The dataset provides the corresponding `.inp` input files, `.out` output files, and `.xyz` structures for the optimized geometries.

### Reference to Manuscript
This dataset accompanies the publication:  
**“Dynamic Behavior of Molecular Pd-acetate Trimers and Dimers in Heterogeneous Vinyl Acetate Synthesis.”**  
**DOI:** https://doi.org/10.1038/s41467-025-66820-7

Data gathered and prepared by Christian Sandoval-Pauker, Postdoctoral Fellow, Smalley-Curl Institute, Rice University, Houston, TX 77005, USA.

## Summary of Methodology
All calculations were performed with ORCA in the gas phase.

- **Geometry optimizations:**  
  PBE0/def2-SV(P) with D3 dispersion and TightSCF

- **Frequency calculations:**  
  PBE0/def2-SV(P) with D3 dispersion and TightSCF

- **Single-point energies:**  
  - TPSSh/def2-TZVP with D3  
  - r2SCANh/def2-TZVP with D3  
  Both run with TightSCF and SlowConv

The repository includes the input files, output files, and `.xyz` structures for all optimized species.

# Cosmic-Sponge
# Structural Relativity - Observational Validation

This repository contains the numerical validation and Python scripts for the "Structural Relativity" framework. The model extends General Relativity by treating the macroscopic vacuum as a porous medium subject to metric yielding and structural fatigue.

## Overview

The provided code replicates the phenomenological tests used to resolve the three major cosmological tensions:
1. **Hubble Tension (H0):** Resolved via geometric defocusing and hemispheric anisotropy analysis.
2. **S8 Tension:** Resolved through the structural decay of the effective gravitational coupling (g_eff).
3. **Dark Matter Anomalies:** Redefined as the optical signature of metric yielding in galaxy lensing.

## Repository Structure

- `lensing_validation.py`: Analyzes SLACS survey data to detect the structural discontinuity gap at z = 0.08.
- `quasar_dispersion.py`: Validates vacuum granularity (approx. 10 nm) using SDSS Quasar chromatic dispersion data.
- `anisotropy_h0.py`: Performs hemispheric segregation on the Pantheon+SH0ES dataset to detect directional yielding in the Hubble flow.
- `requirements.txt`: List of necessary Python libraries.

## Key Results

| Test | Phenomenon | Significance | Improvement vs. LCDM |
|------|------------|--------------|----------------------|
| Galaxy Lensing | Metric Rigidity | 4.2 Sigma | Phase Transition detected |
| Quasar Data | Vacuum Grain | > 5 Sigma | 72x Accuracy increase |
| Supernovae | H0 Anisotropy | 4.2 Sigma | Resolved via Texture |
| Clustering | g_eff Decay | Resolved | 12% reduction at z=0 |

## Installation & Usage

1. Clone this repository:
   ```bash
   https://github.com/ntartaro7-ship-it
2. Install the required libraries (NumPy, Pandas, Matplotlib):
   pip install -r requirements.txt
3. Run the validation scripts:
   python lensing_validation.py
  python quasar_dispersion.py
  python anisotropy_h0.py

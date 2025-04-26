VANDELS UV Line Spectra and Lyman Continuum Predictions from Simulations
==========================================================================

This repository contains the data, code, and plots related to:

**Gazagnes et al. (2024), ApJ 969, 50**  
DOI: https://doi.org/10.3847/1538-4357/ad47a4

Summary
-------

We compare mock ultraviolet C II and Si II line spectra from a high-resolution radiation-hydrodynamical (RHD) simulation to observations of 131 galaxies from the VANDELS survey at z ~ 3.

Key results:
- `The mock spectra successfully reproduce 83% of the observed VANDELS spectra.`
- `Best-matching spectra originate from phases of intense star formation in the virtual galaxy.`
- `Predicted Lyman continuum (LyC) escape fractions (f_esc) are low on average (0.01 ± 0.02), consistent with previous constraints.`
- `LyC leakage is tightly linked to UV-bright, compact, dust-free, and low-neutral-gas regions.`
- `The study validates the use of Si II and C II line spectra as indirect tracers of LyC leakage.`

Reproducing the results requires the simulation data which is not public but can be shared upon reasonable request.

Contents
--------

- `Data/` — Observational data from the VANDELS survey
- `Measurements/` —  The csv files containing the relevant data measurements.
- `Paper/` — Contains the article pdf
- `Notebooks/` — Jupyter notebooks for making the analysis and producing the paper figures
- `Plots/` — Figures from the paper (see examples below)



Figures overview:
-----------------

This is an overview of the main figures in the paper, which are reproducible using the python notebooks. The paper provides the details and context for the interested reader. 

1. General properties comparison:

   .. raw:: html

      <div style="display: flex; justify-content: space-between;">
          <img src="Plots/CompareGlobal.png" width="75%" />
      </div>

2. Lines properties comparison:

   .. raw:: html

      <div style="display: flex; justify-content: space-between;">
          <img src="Plots/EWProp.png" width="60%" />
      </div>

3.  Profile fitting:

   .. raw:: html

      <div style="display: flex; justify-content: space-between;">
          <img src="Plots/fitexamples_V2.png" width="80%" />
      </div>


4. Chi square comparison:

   .. raw:: html

      <div style="display: flex; justify-content: space-between;">
          <img src="Plots/Chisquare_woff_V2.png" width="40%" />
      </div>


5. Escape fractions

   .. raw:: html

      <div style="display: flex; justify-content: space-between;">
          <img src="Plots/Escape_fractions_V2.png" width="45%" />
      </div>

   .. raw:: html

      <div style="display: flex; justify-content: space-between;">
          <img src="Plots/LyaLyc_V2.png" width="45%" />
      </div>


   .. raw:: html

      <div style="display: flex; justify-content: space-between;">
          <img src="Plots/fescSimu.png" width="55%" />
      </div>

6. Stacks

   .. raw:: html

      <div style="display: flex; justify-content: space-between;">
          <img src="Plots/Stacks_V2.png" width="85%" />
      </div>


Citing
------

If you use this code or data, please cite:

Gazagnes et al. (2024), *The Astrophysical Journal*, 969, 50  
https://doi.org/10.3847/1538-4357/ad47a4

License
-------

This work is licensed under the Creative Commons Attribution 4.0 License.
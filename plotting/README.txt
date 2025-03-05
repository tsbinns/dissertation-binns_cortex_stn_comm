Scripts for plotting results and contact locations.

The different files are:
- "dbs_lfp_locations": plot DBS leads in the STN (Figure 3A)
- "ecog_lfp_locations": plot ECoG contacts on the cortex (Figure 3A)
- "fmri_lme_coeffs_indirect_nuclei": plot indirect pathway nuclei according to
  fMRI-LME coefficients (Figure 12)
- "imcoh": plot ImCoh (univariate and multivariate; Figure 6)
- "mic_patterns_hyperdirect_fibres": plot hyperdirect fibres coloured according
  to MIC patterns (Figure 10)
- "mic_patterns": create interpolated MIC patterns and plot raw points (Figures
  6B & 11)
- "power": plot power (univariate and multivariate; Figures 3 & 4)
- "ssd_patterns_dbs_contacts": plot SSD patterns for DBS contacts (Figure 4B)
- "ssd_patterns": create interpolated SSD patterns and plot raw points (Figures
  4A & 5)
- "tde": plot time delay estimates (Figure 9)
- "trgc": plot TRGC (Figures 7 & 8)

There are 2 general types of files:
- "MedOffOn": for comparing OFF therapy and ON levodopa results
- "StimOffOn": for comparing OFF therapy and ON STN-DBS results

Files have some shared constants:
- "FOLDERPATH_ANALYSIS": directory where the analysis settings are stored and
  where the results will be stored (e.g. in "Project/Analysis")
NCDelta — flatCAF analysis
===========================

Purpose
-------
This folder contains analysis code and notes for checking whether the flatCAF 1e20 Monte Carlo sample contains any NC-Delta radiative decay ($(\Delta\rightarrow\gamma)$) signal. It includes a Jupyter notebook that loads selected CAF trees, computes post-selection variables, and produces stacked histograms by true MC category.

Contents
--------
- `explore_flatCAF.ipynb` — interactive notebook used for exploring the CAF and producing stacked histograms.
- `notes.md` — ad-hoc notes for the analysis.
- `output_all.root` (not tracked here) — example ROOT file used in the notebook (path/filename may differ locally).

Category labels used in the notebook
-----------------------------------
The plotting cell uses these categories (indices 0..7) with LaTeX formatting:
- NC $\Delta\rightarrow\gamma$
- Other NC 1$\gamma$X$_p$
- NC $\pi^{0}$
- NC $\pi^{\pm}$
- Other NC
- CC $e$
- Other CC
- No match


Notes & next steps
------------------
- The notebook expects CAF-selected trees from medulla (`events/simulation/selected_1g0p`, `selected_1g1p`). If your file layout differs, adjust the tree paths.
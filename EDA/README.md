# EDA (Exploratory Data Analysis)

This directory holds exploratory work: notebooks, quick scripts, figures and notes created while investigating the dataset(s).

Suggested contents:
- notebooks/ - Jupyter notebooks (.ipynb) with exploratory analysis
- figures/ - generated plots and images
- scripts/ - small helper scripts used during EDA
- raw/ - links or pointers to raw data (do not commit large files)
- processed/ - output produced by EDA (avoid committing large files)

Guidelines:
- Keep the repository free of large data files. Use a data download script or document where to obtain the data.
- Name notebooks clearly (e.g. 01-data-inspection.ipynb, 02-feature-exploration.ipynb).
- Commit derived code (scripts, notebooks) but not large data artifacts. Add instructions here for reproducing figures and results.

Example:
1. Place notebooks in EDA/notebooks/.
2. Use EDA/scripts/download_data.py to fetch data (if applicable).
3. Document any preprocessing steps taken during exploration.

If you want, I can also create sample notebooks or a .gitignore entry for data/ and EDA/raw/.

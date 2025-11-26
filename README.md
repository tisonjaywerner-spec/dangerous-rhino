STR_HousingImpact_HennepinCounty/
│
├── README.md                # Project overview, research question, methods, results summary
├── LICENSE                  # Open-source license (MIT recommended)
├── .gitignore               # Ignore data files, notebooks checkpoints, etc.
│
├── data/                    # Raw and processed datasets
│   ├── raw/                 # Original datasets (Airbnb, VRBO, parcel data, census)
│   └── processed/           # Cleaned/merged datasets ready for analysis
│
├── notebooks/               # Jupyter or R notebooks for analysis
│   ├── 01_data_wrangling.ipynb
│   ├── 02_exploratory_analysis.ipynb
│   ├── 03_regression_modeling.ipynb
│   └── 04_visualizations.ipynb
│
├── src/                     # Reusable scripts
│   ├── data_cleaning.py     # Functions for cleaning datasets
│   ├── merge_datasets.py    # Functions for combining parcel + STR + census data
│   ├── analysis.py          # Regression, correlation, statistical tests
│   └── visualization.py     # Graphs, maps, charts
│
├── reports/                 # Written outputs
│   ├── whitepaper.md        # Full academic-style write-up
│   ├── presentation.pdf     # Slide deck for quick review
│   └── summary.md           # Executive summary for portfolio
│
├── figures/                 # Exported charts, maps, regression plots
│   ├── str_density_map.png
│   ├── housing_price_trends.png
│   └── regression_results.png
│
└── docs/                    # Documentation
    ├── data_dictionary.md   # Definitions of variables
    └── methodology.md       # Detailed methods, assumptions, limitations

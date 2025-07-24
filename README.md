# Climate-Nutrient Interaction Modeling

This project analyzes how rainfall and streamflow affect nitrate concentrations in surface water using real environmental data.

## Features

- Merge and clean daily data from three sources: rainfall, streamflow, and nitrate concentration
- Compute daily nitrate loads based on flow and concentration
- Perform correlation analysis and visualize relationships
- Export clean, publication-ready figures and correlation matrix
- Save results in Excel and PDF formats

## File Structure

```
climate_nutrient_modeling/
├── assets/
│   ├── rainfall_daily.csv
│   ├── flowrate.csv
│   └── nitrate.csv
├── script.py                 # Main analysis script
├── correl_matrix.xlsx        # Excel export of correlation matrix
├── Initial_visualization.pdf
├── Nitrate_load.pdf
├── Nitrate_Vs_Rainfall.pdf
├── requirements.txt
└── README.md
```

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/climate-nutrient-modeling.git
cd climate-nutrient-modeling
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the script:

```bash
python script.py
```

## License

MIT License

## Author

Piya Mohasin

## Citation
Zhang Y. and Collins A. (2024). Processed high resolution rainfall, flow rate, sediment and nitrate concentration data [Data set]. Rothamsted Research.
https://doi.org/10.23637/17dquvlt

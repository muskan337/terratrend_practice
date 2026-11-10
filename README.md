# TerraTrend Practice

A practice repository for exploring and modelling long-term temperature trends.

> **Status:** Early stage. This repo currently contains only the project scaffold.

## Overview

TerraTrend Practice is where I experiment with analysing temperature time-series data: cleaning it, visualising trends, and building simple forecasting models.

<!-- TODO: replace with 2-3 sentences on your exact goal and dataset -->

## Planned Workflow

1. **Load & clean** the dataset
2. **Explore** trends, seasonality and anomalies
3. **Model** with baseline and forecasting approaches
4. **Evaluate** using held-out time periods

## Tech Stack

- Python
- pandas, NumPy
- Matplotlib / Seaborn
- scikit-learn (and time-series libraries as needed)

## Project Structure

```
terratrend_practice/
├── data/          # raw and processed datasets (not tracked if large)
├── notebooks/     # exploration and experiments
├── src/           # reusable scripts and modules
├── README.md
└── .gitignore
```

## Getting Started

```bash
git clone https://github.com/muskan337/terratrend_practice.git
cd terratrend_practice
python -m venv venv
source venv/bin/activate      # Windows: venv\Scripts\activate
pip install -r requirements.txt   # added once dependencies are finalised
```

## Roadmap

- [ ] Add dataset and data-loading script
- [ ] Exploratory analysis notebook
- [ ] Baseline forecasting model
- [ ] Evaluation and results summary

## Author

**Muskan Jain** · [GitHub](https://github.com/muskan337)

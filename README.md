# ML-NBALineupPrediction

## Overview

### Project Objectives

The main objective of this project is to analyze historical NBA lineup data to identify trends and patterns in team performance. By examining lineup stability, player frequency, and matchup outcomes, this analysis aims to provide valuable insights that can be used for predictive modeling and strategic decision-making in basketball analytics.

This project explores NBA lineup prediction and hidden patterns using historical matchup data from multiple seasons. The notebook processes raw game data, extracts key lineup statistics, and performs exploratory data analysis to uncover trends.

## Requirements

Before running the notebook, ensure you have the following installed:

### Python Version:

- Python 3.8 or later

### Required Libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `glob`

You can install the required libraries using:

```sh
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Dataset

The dataset consists of **NBA matchup CSV files** from multiple years (2007-2015). The script automatically loads these files, processes them, and generates useful insights.

### Data Path

- Ensure that all the CSV files are stored in the `data/` directory inside the project folder.
- The notebook looks for files in the format:
  ```
  data/matchups-20XX.csv
  ```
  where `20XX` represents the season year.

## Running the Notebook

### 1. Clone the Repository 

```sh
git clone https://github.com/rrishabsingh02/ML-NBALineupPrediction.git
cd MLNBALineupPrediction
```

### 2. Open Jupyter Notebook

```sh
jupyter notebook
```

Then, open `Saieashan_analysis.ipynb` in Jupyter Notebook.

### 3. Run the Notebook

- Execute all cells **sequentially** to ensure smooth processing.
- The script will:
  1. Load and preprocess the CSV files.
  2. Clean and standardize team acronyms.
  3. Extract unique lineups for each game.
  4. Perform exploratory data analysis on lineup stability, frequency, and impact on outcomes.

### 4. Visualization and Insights

- Several plots are generated to analyze lineup trends.
- Ensure **matplotlib** and **seaborn** are installed to display visualizations correctly.

### 5. Results 
![image](https://github.com/user-attachments/assets/c705f8cf-282c-40b2-bc29-da55aac4b6ed)



## Notes

- If your data directory is different, update the path in the notebook:
  ```python
  data_folder = "../data"  # Change to your dataset location
  ```
- If additional years are available, ensure they follow the naming format (`matchups-20XX.csv`).

## Contact

For any issues, feel free to raise a GitHub issue or reach out to the repository maintainer.

# 🧪 The Great Divide: A/B Testing and Hypothesis Test
This project is a comprehensive review of A/B Testing and the different types of statistical tests used in A/B testing. The analysis can be accessed [here](analysis/the-great-divide-a-b-testing-and-hypothesis-test.ipynb).

**Author**: Po-Hsun (Ben) Chen

## Summary
In this A/B testing project using data from the mobile game "Cookie Cat," we investigated the impact of two different settings on player retention rates and the number of rounds played. Through rigorous statistical analysis, we aimed to discern whether changes in the game's features significantly influenced player engagement metrics, providing valuable insights for game developers seeking to optimize user experience and player longevity.

## Data Source
The dataset used in this analysis contains information on the gaming data by random users. The dataset contains the game version (the target that we're trying to test), the number of game rounds played and the retention. The dataset used in this analysis is sourced from Kaggle. You can access the dataset [here](https://www.kaggle.com/datasets/yufengsui/mobile-games-ab-testing).

## Dependencies
All required dependencies are listed in this [conda environment file](environment.yaml).

## How to Reproduce the Analysis
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/phchen5/cookie-cats-ab-test.git
   cd cookie-cats-ab-test
   ```
2. **Download the Dataset from the Source:**
   You may need to register for a Kaggle account. After you've downloaded the dataset, place the `cookie_cats.csv` file within a `data/` folder located in the root. You may also place it anywhere else in the repository as you like, just be sure to edit the data source path within the analysis.
3. **Set Up and Activate Environment:**
   ```bash
   conda env create -f environment.yaml
   conda activate cookie-cat
   ```
4. **Open the Notebook:**
   ```bash
   jupyter lab analysis/the-great-divide-a-b-testing-and-hypothesis-test.ipynb
   ```
5. **Run the Cells and Have Fun Exploring!**

## Files
- `analysis/the-great-divide-a-b-testing-and-hypothesis-test.ipynb`: Jupyter notebook containing the EDA code.
- `environment.yaml`: Conda environment file listing required dependencies.



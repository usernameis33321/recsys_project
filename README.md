# Recommender Sysytem Course Project Work
Li Ryoyan : 150181484

## How to Run：
  1. Open source_file.ipynb in Google Colab or Jupyter Notebook.
  2. Make sure the dataset files are placed in the correct directory.
  3. Run the notebook cells in order to reproduce the experiments and results.

## Before you run part 2:
To run part 2, you need to run these cells before runing part 2 at least:
- cells to find paths, include open datasets
- split data into train, val and test sets
- setup part for baselines in part 1
- evaluation metrics (named as evaluate_model)

## Enviroment:
 - Python 3.x
## Python packages:
 - pandas
 - numpy
 - scikit-learn
 - matplotlib
 - seaborn
## Data:
 - MovieLens 1M Dataset (https://grouplens.org/datasets/movielens/1m/)
## Path:
I developed and tested the code in Google Colab. The code automatically detects the environment and adjusts the file paths accordingly.

Before running the notebook, make sure you have downloaded the **MovieLens 1M dataset (ml-1m)** and placed the following three files in a folder named `data` in the same directory as the notebook:

- `ratings.dat`
- `movies.dat`
- `users.dat`

The directory structure should look like this:

```text
recsys-project/
├── README.md
├── source_file.ipynb
└── data/
    ├── ratings.dat
    ├── movies.dat
    └── users.dat
```
For now, the source_file still named as part1, and it will change to source_file before final submition.


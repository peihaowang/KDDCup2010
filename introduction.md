# Introduction

Our program includes Condensed part and Sparse part. They are separate from each other(We tried to ensemble them but the result is no better).

## Condensed

To run the condensed part, first get condensed features. There are 2 ways:

1. Directly use `agg_train.csv` and `agg_test.csv` provided in the `agg_data.zip` (recommended)

2. Run `Condensed_features.ipynb` line by line, then save them. Then, with condensed features, run `random_forest.ipynb`.

## Sparse

To run the sparse part:

Since sparse features are of high dimensionality, the storage in `.csv` could be terribly storage consuming. So it's recommended that run `sparse_features.ipynb` cell by cell, and review the output below the code lines.

## Checkup

Our predictions for unkown records are stored in `data/predict_result.csv`, please check this file instead of `data/test.csv`.




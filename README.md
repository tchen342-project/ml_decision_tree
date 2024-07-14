I implemented decision trees and random forests from scratch to classify datasets including spam and Titanic survivors. I designed my own decision tree structure, managed categorical features by encoding them appropriately, and handled missing values using imputation methods to retain data integrity.
For decision tree training, I incorporated a maximum depth stopping criterion to prevent overfitting, and extended this to random forests by aggregating multiple decision trees with bootstrap sampling.
Performance was evaluated by training and validating both classifiers, reporting accuracy metrics for each dataset to assess model effectiveness.
See [Decision_tree.ipynb](Decision_tree.ipynb) for the code.

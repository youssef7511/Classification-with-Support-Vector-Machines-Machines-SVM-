# Classification-with-Support-Vector-Machines-Machines-SVM-
what i did :/
1. Load the BilletsBanque.xls file containing the data
2. Display the first lines of the dataset using head()
3. Check for missing values
4. Use describe() to obtain a statistical summary of the variables.
5. Plot the distribution of each variable using histograms
6. Use a pairplot (sns.pairplot) coloured according to class to visualise the relationships between
variables.
7. Draw a correlation matrix
8. Separate the features (X) and the target (y)
9. Divide data into train/test (70% learning, 30% test)

3

10. Apply normalisation (standardisation) with StandardScaler.
11. Use SVC(kernel="linear") to train a classifier.
12. Evaluate performance on test data with accuracy_score, confusion_matrix and
classification_report
13. Is a linear separation sufficient to distinguish true/false tickets?
14. Using different kernels (poly, sigmoid)
15. Use SVC(kernel="rbf") and test different C parameters: (e.g.: 0.1, 1, 10, 100) and
gamma: (e.g.: 0.01, 0.1, 1, 10)
16. What are the best values for c and gamma?
17. Compare the scores, confusion matrices and classification ratios of the four
models to choose the best model.

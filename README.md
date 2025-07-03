# Machine Learning Analysis of HELOC Data

## Overview

This project focuses on building an Interpretable Machine Learning (IML) model using the Home Equity Line of Credit (HELOC) dataset. The goal is to achieve high prediction accuracy while providing clear explanations for model decisions, emphasizing the importance of interpretability in financial contexts.

## Home Equity Line of Credit (HELOC) Dataset

The Home Equity Line of Credit (HELOC) dataset contains anonymized information about HELOC applications. A HELOC is a line of credit secured by a homeowner's equity. This dataset is commonly used for credit risk analysis, predicting whether applicants will repay their credit lines.

The dataset in this project includes two files:

-   `data/HelocData.csv`: Contains the main dataset with features related to borrower characteristics and credit behavior.
-   `data/HelocDataDict.xlsx`: Provides a description of each feature in the CSV file.

## Requirements

To run this project, install the following Python packages:

- numpy
- pandas
- matplotlib
- seaborn
- scipy
- scikit-learn
- pygam
- eli5
- pycebox
- shap

You can install the required packages using the following command:

```bash
pip install -r requirements.txt
```

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

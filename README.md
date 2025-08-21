# Random Forest Classification - Glass Dataset

This repository is focused on implementing Random Forest Classification on the glass.csv dataset.  
The assignment demonstrates preprocessing, model building, evaluation, and comparison of ensemble methods like bagging and boosting.

---

## Objective
To build a classification model using the Random Forest algorithm for predicting the type of glass based on its chemical properties.  
This assignment provides hands-on practice with ensemble learning methods and model evaluation.

---

## Files Included

| File Name                  | Description |
| -------------------------- | ------------------------------------------------------------ |
| RandomForest.ipynb          | Jupyter Notebook containing preprocessing, Random Forest implementation, bagging & boosting comparison |
| Random Forest.docx          | Word document containing the problem statement and assignment details |
| glass.csv                   | Dataset containing chemical composition features and glass type labels |

---

## Dataset Description

The Glass dataset contains chemical analysis results of glass samples with the following attributes:

- **RI:** Refractive Index  
- **Na:** Sodium  
- **Mg:** Magnesium  
- **Al:** Aluminum  
- **Si:** Silicon  
- **K:** Potassium  
- **Ca:** Calcium  
- **Ba:** Barium  
- **Fe:** Iron  
- **Type:** Glass type (class attribute)  
  - 1 = Building windows (float processed)  
  - 2 = Building windows (non-float processed)  
  - 3 = Vehicle windows (float processed)  
  - 4 = Vehicle windows (non-float processed) *(none in dataset)*  
  - 5 = Containers  
  - 6 = Tableware  
  - 7 = Headlamps  

---

## Tools & Libraries
* Jupyter Notebook  
* Python 3.x  
* Libraries: pandas, matplotlib, seaborn, scikit-learn  

---

## Tasks Performed
* EDA: explored dataset structure, checked missing values, outliers, and correlations  
* Data Visualization: histograms, boxplots, and pairplots to study distributions and relationships  
* Data Preprocessing: handled missing values, applied encoding (if needed), scaled features, and addressed imbalance  
* Random Forest Model: trained classifier, evaluated using accuracy, precision, recall, F1-score  
* Bagging & Boosting: implemented ensemble techniques and compared results with Random Forest  
* Analysis: explained differences between bagging and boosting, and discussed strategies for handling imbalance  

---

## Status
Completed – dataset analyzed, Random Forest model implemented, bagging/boosting compared, and insights derived.  
This assignment provides practical exposure to ensemble learning methods in classification tasks.

---

## Author
Nuzhat – Data Science Learner  
GitHub: [nuzhatt05](https://github.com/nuzhatt05)


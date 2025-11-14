## 1. Classification & Clustering (McDonald's India Menu)

Notebook: `nutrition_classification_clustering.ipynb`  

- **Dataset:** McDonald's India Menu Nutrition Facts  
  - https://www.kaggle.com/datasets/tusharbhardwaj/mcdonalds-india-menu-nutrition-facts  
  - Mirror: https://www.kaggle.com/datasets/deepcontractor/mcdonalds-india-menu-nutrition-facts
- **Models used:**
  - Decision Tree (binary: healthy vs unhealthy)
  - Random Forest
  - K-Means clustering
  - Agglomerative clustering
- **Evaluation:** accuracy, precision, recall, F1-score, confusion matrices, silhouette scores

- ## 2. Association Rule Mining (Store Sales)

Notebook: `store_association_rules.ipynb`  

- **Dataset:** Store Sales Forecasting  
  - https://www.kaggle.com/datasets/cavinlobo/stores-sales-forecasting-dataset
- **Techniques:**
  - Basket construction at different granularities (e.g., Customer × Product)
  - Apriori / FP-Growth + fallback pairwise rules
  - Support, confidence, lift used to mine strong rules.

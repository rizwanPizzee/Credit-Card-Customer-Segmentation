# Credit Card Customers Segmentation

## Purpose

This Jupyter notebook performs exploratory data analysis (EDA), preprocessing and unsupervised customer segmentation on a credit-card customers dataset. The main goal is to find meaningful customer clusters using K‑Means, evaluate cluster quality with several metrics and visualize the segmentation in 2D using PCA.

---
## View The Nootbook
* Link 1: https://github.com/rizwanPizzee/Credit-Card-Customer-Segmentation/blob/master/Credit-Card-Customers.ipynb
* Link 2: https://rizwanpizzee.github.io/Credit-Card-Customer-Segmentation/

## Dataset

- **Filename used in the notebook:** `creditCardCust.csv` (Link: https://www.kaggle.com/datasets/arjunbhasin2013/ccdata)

---

## Project structure (files)

- `Credit-Card-Customers.ipynb` — main analysis notebook
- `creditCardCust.csv` — dataset

---

## Tools / Tech stack

- **Language:** Python
- **Notebook environment:** Jupyter Notebook
- **Libraries used:**

  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

---

## ML models & techniques used

- **K‑Means clustering** — primary unsupervised learning algorithm used to segment customers into clusters.

  - `n_init` and `random_state` are set in the notebook for reproducibility.
  - Several values of `k` are evaluated (range 2–10) to choose the best number of clusters.

- **Principal Component Analysis (PCA)** — used to reduce dimensionality to 2 components for visualization of clusters.

- **Evaluation metrics for clustering:**

  - **Inertia** — for elbow method
  - **Silhouette Score** — higher means better-defined clusters
  - **Davies–Bouldin Score** — lower values indicate better clustering

---

## Reproducing & running locally

1. Clone or download the repository (or put the notebook and dataset in one folder).
2. Make sure `creditCardCust.csv` is present in the same folder as `Credit-Card-Customers.ipynb`.
3. (Optional) Create and activate a virtual environment.
4. Install dependencies (python, pandas, numpy, matplotlib, seaborn, scikit-learn)
5. Run the notebook from top to bottom (or Run All)

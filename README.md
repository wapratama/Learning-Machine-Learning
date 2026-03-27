# Learning-Machine-Learning: My Machine Learning Portfolio

> Hands-on exploration of core Machine Learning concepts through structured notebooks, real datasets, and reproducible experiments.

## About

I'm building this repository as a learning-by-doing ML portfolio, exploring classical and modern ML techniques with clean, well-documented Jupyter notebooks. Each module covers a core ML area with multiple algorithms, real datasets, and visual explanations.

**Tech Stack:**

![Python](https://img.shields.io/badge/Python-3.11-blue)
![scikit-learn](https://img.shields.io/badge/scikit--learn-latest-orange)
![uv](https://img.shields.io/badge/uv-package%20manager-green)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![VSCode](https://img.shields.io/badge/VSCode-Editor-blue)

---

## Workflows

My approach for a typical machine learning workflow. Each phase is crucial for ensuring that the model developed is robust, efficient, and capable of delivering accurate predictions. 

![ML Workflow](/Machine%20Learning%20Workflow.png)

Notes: For this repo, I am not fully demonstrate this full workflows.

---

## Modules

| Module | Topics Covered | Status |
|--------|----------------|--------|
| [Regression](./01-Regression/) | Linear, Polynomial, Ridge, Lasso | 🔄  Active / In Progress |
| [Classification](./02-Classification/) | Logistic, Decision Tree, Random Forest, SVM | 🔄  Active / In Progress |
| [Clustering](./03-Clustering/) | K-Means, Hierarchical, DBSCAN | 🔄  Active / In Progress |
| [Feature Engineering](./04-FeatureEng/) | Encoding, Scaling, Selection, PCA | 📅 Planned |
| [Hyperparameter Tuning](./05-Hyperparam/) | GridSearch, RandomSearch | 📅 Planned |

---

## Setup & Reproduction

All experiments are fully reproducible using `uv`:

```bash
# Clone the repo
git clone https://github.com/wapratama/Learning-Machine-Learning.git
cd Learning-Machine-Learning

# Create environment and install all dependencies (takes ~30 seconds)
uv venv
uv sync

# Register Jupyter kernel
uv run python -m ipykernel install --user --name=ml-portfolio

# Launch Jupyter (Choose one: Lab or Notebook)
uv run jupyter lab
uv run jupyter notebook
```
> Note: No manual venv activation needed.
Always use uv run prefix to run scripts and commands.

### Download the data
Data Source: Kaggle
- Method 1: Using Kaggle API
  
  Authenticate first before using Kaggle API: Read instruction [here](https://github.com/Kaggle/kaggle-cli/blob/main/docs/README.md).

- Method 2: Manual Download

  Simply manual download it from the link above (click **Download** or **Download All**), unzip and place it under your data folder.

---

## Key Learnings & Highlights

### 01. Regression
*(Active / In Progress)*

### 02. Classification
*(Active / In Progress)*

### 03. Regression
*(Active / In Progress)*

### 04. Feature Engineering
*(Planned)*

### 05. Hyperparameter Tuning
*(Planned)*

---

## Resources & References

- [Dicoding ML for Beginner (in Bahasa)](https://www.dicoding.com/academies/184-belajar-machine-learning-untuk-pemula)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)
- [Hands-On Machine Learning — Aurélien Géron](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/)
- [Practical Deep Learning (fast.ai)](https://course.fast.ai/)
- [Kaggle Learn](https://www.kaggle.com/learn)
- [Pandas Documentation](https://pandas.pydata.org/pandas-docs/stable/reference/io.html)

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://www.linkedin.com/in/wisnu-anugrah-pratama/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black)](https://github.com/wapratama)

---
# ML-Post-Prunning-Notebook

**🌸 Iris Dataset Decision Tree Classifier**

This project implements a classification model using the **Decision Tree algorithm** on the popular **Iris dataset**. The goal is to classify iris flowers into one of three species: *Setosa*, *Versicolor*, and *Virginica*, using various flower measurements.

## 🧰 Libraries Used

- pandas
- numpy
- seaborn
- scikit-learn
- matplotlib

## 📊 Dataset

Two versions of the Iris dataset are used:

1. `sklearn.datasets.load_iris()` — built-in version from scikit-learn
2. `seaborn.load_dataset('iris')` — alternative version from Seaborn library

## ⚙️ Workflow

1. **Load dataset** from scikit-learn and Seaborn
2. **Extract features** (`X`) and target values (`Y`)
3. **Train/Test Split** using `train_test_split()` with 80/20 ratio
4. **Train Decision Tree Classifier** with `max_depth=3` to perform post-pruning
5. **Visualize** the trained tree using `matplotlib` and `sklearn.tree.plot_tree`

## 🌳 Tree Pruning

The model uses `max_depth=3` to control tree growth and reduce overfitting. This is a form of *post-pruning*, where the depth of the tree is restricted during training.

## 📈 Visualization

The decision tree structure is visualized to better understand how the model makes predictions based on the input features.

## 🚀 Running the Code

Make sure all required libraries are installed:

```bash
pip install pandas numpy seaborn scikit-learn matplotlib


# 🪵 TimberTrek: Interpretable Sparse Decision Tree Visualizations for NAFLD Prediction
...

## 🧭 Project Overview

This project presents an explainable AI framework using **sparse decision trees** trained with the **TIMBERTREK** library on a clinical dataset related to **Non-Alcoholic Fatty Liver Disease (NAFLD)**. We focus on **transparent model interpretation** through visualization of diverse trees from the **Rashomon set**—a collection of equally accurate yet structurally distinct decision trees.

---

## 🎯 Objectives

- Train sparse decision trees for **NAFLD classification**
- Explore the **Rashomon set** for model diversity
- Enable **clinically interpretable decisions**
- Support **human-in-the-loop model selection**

---

## 📌 Key Features

- ✅ **Sparse Tree Generation**: Efficiently produces hundreds of shallow trees using TreeFARMS.
- 🌳 **Interpretable Visualizations**: Visualizes each tree with meaningful structure, feature splits, and decisions.
- 🩺 **Clinical Relevance**: Operates on a real-world NAFLD dataset to support healthcare decision-making.
- 📁 **Rashomon Set Analytics**: Stores diverse trees in JSON format with node/leaf/feature statistics for downstream analysis.

---

## 🗂️ Repository Structure

| Path | Description |
|------|-------------|
| `preProcess_dataset.ipynb` | Preprocessing of raw NAFLD data |
| `decision_tree_generation.ipynb` | Sparse decision tree training with TreeFARMS |
| `timber_trek_on_nafld.ipynb` | Visualization of trees and Rashomon set analysis |
| `nafld1.csv`, `nafld_timbertrek_1.csv` | Input NAFLD clinical datasets |
| `all_sparse_trees.json` | Collection of sparse decision trees (features, nodes, leaves) |
| `visualization/` | Rendered decision tree diagrams (`tm1.png`, `tm6.png`, etc.) |
| `requirements.txt` | Python dependencies |

---

## 📊 Tree Visualization Samples

<p align="center">
  <img src="visualization/tm1.png" width="400"/>
  <img src="visualization/tm6.png" width="400"/>
  <img src="visualization/fulltree.png" width="800"/>
</p>

Each tree corresponds to a unique structure in the Rashomon set and highlights different feature combinations for classification.

---

## ⚙️ Getting Started

### 🛠️ Requirements
- Python 3.8+
- Jupyter Notebook
- TIMBERTREK, TreeFARMS
- Core libraries: `pandas`, `numpy`, `matplotlib`, `scikit-learn`, `plotly`

### 📦 Install Dependencies
```bash
pip install -r requirements.txt




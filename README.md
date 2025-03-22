# Principal Component Analysis (PCA) — Visualized & Explained

This notebook provides a complete mathematical and practical walkthrough of **Principal Component Analysis (PCA)**. It includes:

- ✅ A **clear derivation** of the PCA objective from first principles
- 📐 An explanation of PCA as an **axis transformation**, not just dimensionality reduction
- 📊 A 2D synthetic example visualizing how PCA rotates axes based on data variance
- 🧠 A hands-on application on the **Olivetti Faces dataset**, demonstrating the concept of **Eigenfaces**

---

## 🧠 What is PCA?

Principal Component Analysis is often introduced as a **dimensionality reduction** technique — but more precisely, it's a **linear transformation** that reorients the data along directions of **maximum variance**. When used for dimensionality reduction, PCA helps retain the most informative components.

This project emphasizes that PCA is not inherently about reduction, but is incredibly useful for it.

---

## ✨ What You’ll Find in This Notebook

### 📐 Derivation from Scratch
- Definition of the PCA optimization objective
- Reformulation using covariance and trace
- Solution via eigenvalue decomposition

### 📉 Visualization of PCA
- 2D synthetic dataset with clearly visualized principal axes
- Projections along individual components

### 👤 Eigenfaces Demo
- Use of PCA on the **Olivetti Faces** dataset
- Dimensionality reduction from 4096 to 50 features
- Reconstruction of original faces from compressed PCA features
- Visualization of the **first 50 eigenfaces**

---

## 📁 Structure
- `Principal_Component_Analysis_(PCA).ipynb`: Full notebook with explanations, math, and code
- No additional dependencies beyond `numpy`, `matplotlib`, and `scikit-learn`

---

## 📌 Applications of PCA
- Dimensionality reduction
- Noise filtering
- Data visualization
- Feature compression
- Face recognition (Eigenfaces)

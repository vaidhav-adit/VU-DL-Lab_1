# Lab 1: Tensors & Datasets

## 📘 **Overview**

This is the **first lab work** designed to kickstart your journey into **Deep Learning**. 

This notebook introduces the fundamental building blocks of neural networks: **Tensors** and **Data Pipelines**. It serves as a practical guide to understanding how data is structured and manipulated before being fed into a model.

> **Note:** This lab is implemented using **PyTorch**, but the core concepts (tensor manipulation, broadcasting, data loading) are universal and apply equally to **TensorFlow**.

---

## 🔑 **Key Concepts Covered**

### **1. Tensors**
The notebook explains the definition and structure of tensors, which are the primary data structure in Deep Learning.
* **Rank (ndims):** Understanding dimensions (e.g., Rank-3 for Color Images).
* **Shape:** How to read and modify the size of a tensor.
* **Data Types:** Working with `float32` and other standard types.

### **2. Tensor Operations**
You will learn to perform essential mathematical and structural operations:
* **Creation:** Converting Python lists to tensors and initializing random/zero tensors.
* **Reshaping:** Changing tensor dimensions (e.g., `reshape`, `flatten`) to fit model layers.
* **Broadcasting & Batching:** Adding dimensions (`unsqueeze`) to create batch or channel axes.

### **3. Data Loading & Pipelines**
The lab covers how to handle large datasets efficiently:
* **MNIST Dataset:** Downloading and processing real-world handwritten digit data.
* **Transformations:** converting images to tensors and normalizing pixel values.
* **DataLoaders:** Creating iterators that handle batching and shuffling automatically.


## 🚀 **Getting Started**

1.  Ensure your Python environment (PyTorch) or (TensorFlow) is activated.
2.  Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
3.  Open **`Lab1_Tensors_datasets.ipynb`** and run the cells sequentially.

**Happy Learning!**

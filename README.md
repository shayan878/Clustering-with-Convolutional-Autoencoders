# Clustering with Convolutional Autoencoders (MNIST & Fashion-MNIST)

This notebook explores **unsupervised feature learning and clustering** using convolutional autoencoders on the MNIST and Fashion-MNIST datasets.

---

## 📘 Overview
- Train a **convolutional autoencoder** to compress and reconstruct images  
- Use **latent features** for clustering with **K-Means**  
- Evaluate cluster quality with **silhouette score**  
- Visualize reconstructed images and cluster assignments  

---

## 🚀 Quick start
```bash
pip install torch torchvision numpy matplotlib scikit-learn
jupyter notebook clustering_convolutional_autoencoders.py
⚙️ **Expected Results:**
a. Gradual decrease in reconstruction error during training
b. Latent features enable meaningful clusters in MNIST/Fashion-MNIST
c. Silhouette analysis suggests optimal cluster count (~6–7)

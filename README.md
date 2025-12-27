# 🦟 Malaria Cell Detection with Deep Learning

Ce projet utilise un réseau de neurones **EfficientNet** (PyTorch) pour détecter si une cellule est infectée par le parasite de la malaria.

## 📊 Résultats
* **Précision (Accuracy) :** 97%
* **AUC Score :** 0.90+
* **Technique :** Transfer Learning & Fine-Tuning

## 🧠 Modèle
J'ai utilisé une architecture personnalisée :
* **Backbone :** EfficientNet-B0 (Pre-trained)
* **Tête de classification :** Dropout + Global Average Pooling
* **Optimisation :** AdamW + Gradual Unfreezing + Seuil de sécurité médicale (0.1)

## 📂 Données
Le dataset provient de Kaggle : [Cell Images for Detecting Malaria](https://www.kaggle.com/datasets/iarunava/cell-images-for-detecting-malaria).

## ⚙️ Installation & Configuration
Pour lancer ce projet, vous aurez besoin de votre propre clé API Kaggle.
1. Ouvrez le notebook.
2. Téléchargez votre fichier `kaggle.json` depuis votre compte Kaggle.
3. Lancez le notebook et uploadez votre clé quand demandé.
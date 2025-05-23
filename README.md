# Multimodel Fusion Strategies: LSTM, BERT, CNN, ResNet

This repository explores **multimodal fusion strategies** using a combination of LSTM, BERT, CNN, and ResNet models for improved performance in classification tasks.

## Fusion Strategies

We implement and compare two types of fusion strategies:

### 🔹 Late Fusion (Decision-Level Fusion)
In this approach, outputs from different models are fused at the decision level (e.g., after classification probabilities are generated).

1. **LSTM + CNN**
2. **LSTM + ResNet**
3. **BERT + CNN**
4. **BERT + ResNet**

### 🔹 Early Fusion (Feature-Level Fusion)
Here, features from different models are combined before classification.

5. **LSTM + CNN**
6. **LSTM + ResNet**
7. **BERT + CNN**
8. **BERT + ResNet**

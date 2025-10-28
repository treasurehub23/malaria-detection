# Malaria-cell-detection
Malaria Cell Image Classification Using Convolutional Neural Networks (CNN)


### Project overview 
This project detects malaria infection in human blood smears using deep learning techniques, specifically Convolutional Neural Network built with tensorflow and keras. The main objective is to accurately classify cell images as either Parasitized (infected by malaria parasites) or Uninfected, thereby aiding early diagnosis and reducing manual workload for medical experts.

### Dataset
- Source: Kaggle
- Size: 27,000 images didvivded into two categories of "Parasitized" and "Uninfected"
- The dataset was balanced with a 50: 50 proportion

### Processing steps
- Images were rescaled from [0, 255] to [0, 1] 
- The dataset was split into training (80%) and validation (20%) subsets.
- Data batching and shuffling were used to ensure efficient training

### Key Features
- Input shape: 64×64×3 RGB images
- Activation function: ReLU for hidden layers, Sigmoid for output layer
- Regularization: Dropout (0.5) to prevent overfitting
- Optimizer: Adam (learning rate = 0.001)
- Loss function: Binary Crossentropy
- Metric: Accuracy

### Result and Performance
- **Training accuracy** - 95%
- **Validation accuracy** - 95%


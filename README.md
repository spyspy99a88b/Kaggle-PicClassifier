# Kaggle Machine Learning Pictures Classifier

# Installation 

```bash
import keras
```

# Descriptions
It is a machine learning classifier which diagnoses patients with COVID-19, viral pneumonia, and bacterial pneumonia from images of chest X-rays.
The machine learing pics classifier is based on CNN, CNN with dropout and ResNet(residual network).All of the models are realized by keras.

# Data
The training data includes 1127 chest xrays drawn from several different sources (of varying size and quality) and a set of multiclass labels indicating whether each patient was healthy or diagnosed with bacterial pneumonia, viral pneumonia, or COVID-19. The test data includes 484 images without labels, for which you will predict a diagnosis.

# Results
| Models | Accuracy | Val Accuracy |  
| ----- | ----- | ----- |    
| CNN | 0.9980 | 0.6637 |  
| CNN with dropout | 0.8274 | 0.6814|  
| ResNet | 1.0 | 0.6372 | 


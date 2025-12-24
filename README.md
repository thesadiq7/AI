# Task 13: CIFAR-10 Image Classification (4 Classes)

**Student:** Sadiq Quluzade 
**ID:** 4
**Seed:** 13  

## Presentation
[View Presentation Slides](https://docs.google.com/presentation/d/14VjKdVr7wUNhOyx9huhCaiKowSHUpAT2/edit?usp=sharing&ouid=116633181489768191338&rtpof=true&sd=true)

## Dataset
- **Name:** CIFAR-10 (Subset)
- **Classes:** 4 (airplane, automobile, ship, truck)
- **Training samples:** 20,000  
- **Test samples:** 4,000  

## Model Architecture
- **Type:** Convolutional Neural Network (CNN)
- **Convolutional layers:** 6
- **Fully connected layers:** 2
- **Total parameters:** ~1.2 million

## Training Comparison

### Version 1
- **Learning rate:** 0.001
- **Batch size:** 32
- **Optimizer:** Adam
- **Test accuracy:** 82.4%

### Version 2
- **Learning rate:** 0.0005
- **Batch size:** 64
- **Optimizer:** Adam
- **Test accuracy:** 89.1%

### Best Result
- **Best version:** Version 2
- **Final test accuracy:** 89.1%
- **Target accuracy:** 88%
- **Status:** ✓ Achieved

## Analysis
- **Best performing class:** Automobile  
- **Worst performing class:** Ship  
- **Key observations:**  
  The model performs best on automobile images due to clear and consistent visual features.  
  Ship images are more challenging because they often appear in complex backgrounds such as sea and sky, leading to confusion with airplane or truck classes.


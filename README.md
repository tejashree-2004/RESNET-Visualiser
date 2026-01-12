# RESNET-Visualiser

This project was developed during my AI/ML Research Internship at Carnegie Mellon University (USA).  
It focuses on visualizing internal layers of a ResNet deep learning model to understand how convolutional neural networks process images.

The goal is to make deep vision models more transparent by showing how features evolve across layers.

---

## What this project does

This system:
- Loads a pre-trained ResNet model
- Passes an image through the network
- Extracts intermediate feature maps
- Visualizes activations at different layers
- Shows how the model builds visual understanding

This allows us to see:
- What edges and textures the model detects
- How shapes and patterns emerge
- How abstract features are formed in deeper layers

---

## Why this matters

Deep neural networks are often considered “black boxes”.  
This project turns them into **observable systems** by showing what each layer learns.

It is useful for:
- Debugging CNN models
- Improving model trust
- Understanding failure cases
- Teaching deep learning

---

## Core AI concepts used

- Convolutional Neural Networks (CNNs)
- ResNet architecture
- Feature maps
- Activation visualization
- Deep learning interpretability

---

## Tech stack

- Python  
- PyTorch  
- OpenCV  
- NumPy  
- Matplotlib  

---

## How to run

Install dependencies:

```bash
pip install torch torchvision opencv-python matplotlib
Run the visualiser:

bash
Copy code
python main.py --image sample.jpg
This will generate feature map visualizations from different ResNet layers.

Research context
This project was developed during my AI/ML Research Internship at Carnegie Mellon University as part of research on model interpretability and deep vision systems.

Example use cases
Understanding what CNNs see in medical images

Analyzing why a model misclassifies an object

Teaching deep learning visually

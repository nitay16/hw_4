# Assignment 4: Flower Classification using Transfer Learning

## Project Overview
This project applies **Transfer Learning** using **YOLOv5** and **VGG19** to classify flowers from the **Oxford 102 Flowers Dataset**. The objective is to achieve at least **70% test accuracy** using pretrained CNN models.

## Students
- **Nitay Yakoby** - 206102519
- **Kalanit Segal** - 318550100

## Repository Links
- **GitHub Repository:** [Link](https://github.com/nitay16/hw_4)
- **Google Colab Notebook:** [Link](https://colab.research.google.com/drive/1gQEdaHNTJLI5xeQrydWM9KUODyQOdLMl?usp=sharing)

## Project Steps
1. Downloaded the **Oxford 102 Flowers Dataset** from the [official site](https://www.robots.ox.ac.uk/~vgg/data/flowers/102/).
2. Preprocessed the dataset, including image resizing and normalization.
3. Implemented **YOLOv5** and **VGG19** for flower classification.
4. Trained and validated the models using multiple dataset splits.
5. Evaluated accuracy and cross-entropy loss for all models.

## Results
The final test accuracies achieved:

| Model  | Split 0 | Split 1 | Split 2 | **Average** |
|--------|---------|---------|---------|------------|
| **VGG19** | 86.2% | 86.8% | 86.2% | **~86.4%** |
| **YOLOv5** | 92.1% | 91.9% | 92.8% | **~92.3%** |

## Submission Contents
The submitted ZIP file contains:
- This **README.md** file.
- A **PDF report** explaining the solution and results in detail.
- Links to the **source code** and **datasets**.



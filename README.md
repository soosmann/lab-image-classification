# Image Classification Lab

A university lab exploring image classification with **Python and PyTorch**, from training a simple convolutional neural network to transfer learning and data augmentation. Experiments use **MNIST**, **CIFAR-10**, and **Alien vs Predator**, with learning curves, confusion matrices, and t-SNE visualizations to examine model performance.

## Notebooks

| Notebook | Focus |
| --- | --- |
| [Lab 1.1](src/lab1.1.ipynb) | Simple CNN for handwritten digit classification on MNIST; training, checkpoints, and error analysis. |
| [Lab 1.2](src/lab1.2.ipynb) | Adapted AlexNet and ResNet architectures for CIFAR-10. |
| [Lab 1.3](src/lab1.3.ipynb) | ResNet-50 transfer learning on Alien vs Predator: feature extraction, SVM classification, and fine-tuning. |
| [Lab 1.4](src/lab1.4.ipynb) | Visual exploration of image augmentation, including rotation, random erasing, color jitter, and five-crop evaluation. |
| [Lab 1.5](src/lab1.5.ipynb) | Experiments with data augmentation when training a ResNet on CIFAR-10. |

The accompanying [lab report](docs/Hofmann_Marcel_Celaya_Carlos.pdf) documents the experiments and findings.

## Running the notebooks

Open a notebook in **Google Colab** and run its cells in order. Enable a GPU runtime for training and follow the notebook's dataset download instructions. Some cells use Colab-specific paths or Google Drive mounts; adjust these for your environment.

The main libraries are PyTorch, torchvision, NumPy, Matplotlib, scikit-learn, Pillow, and seaborn.

## Acknowledgments

Based on lab materials by Pablo Carballeira at Universidad Autónoma de Madrid, with adaptations from Kevin McGuinness, Ben Trevett, and Dhruvil Karani, as credited in the notebooks.

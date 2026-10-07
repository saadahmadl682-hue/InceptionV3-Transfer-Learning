\# InceptionV3 Transfer Learning – Scene Classification



A deep learning project for \*\*scene classification using Transfer Learning with InceptionV3\*\*. The model was trained to classify images into six different scene categories using a pre-trained InceptionV3 network.



\## 📌 Project Overview



Instead of training a convolutional neural network completely from scratch, this project uses \*\*InceptionV3\*\*, a CNN pre-trained on ImageNet, as the foundation for image classification.



Transfer learning allows the model to reuse features learned from a large dataset and adapt them to a new classification task.



\### Workflow



\*\*Input Image → InceptionV3 → Feature Extraction → Classification Layers → Predicted Scene\*\*



\## 🗂️ Dataset



The project uses a scene classification dataset containing six categories:



\* Buildings

\* Forest

\* Glacier

\* Mountain

\* Sea

\* Street



The dataset was divided into training and testing sets.



> The dataset is not included in this repository because of its size.



\## 🧠 Model



The project uses \*\*InceptionV3 Transfer Learning\*\*.



Key steps:



1\. Load the pre-trained InceptionV3 model.

2\. Use the ImageNet-trained network to extract visual features.

3\. Add classification layers for the six scene categories.

4\. Train the classification layers on the scene dataset.

5\. Evaluate the trained model on unseen test images.

6\. Use the trained model to make predictions on individual images.



\## 📊 Results



The trained model achieved approximately:



| Metric             |        Result |

| ------------------ | ------------: |

| Test Accuracy      |     \*\*90.8%\*\* |

| Test Loss          |    \*\*0.2616\*\* |

| Example Prediction | \*\*Buildings\*\* |

| Example Confidence |    \*\*98.83%\*\* |



\### Example Prediction



The model correctly classified a test image as:



\*\*Buildings — 98.83% confidence\*\*



\## 🛠️ Technologies Used



\* Python

\* TensorFlow

\* Keras

\* InceptionV3

\* NumPy

\* Pandas

\* Matplotlib

\* Jupyter Notebook



\## 📁 Project Structure



```text

InceptionV3-Transfer-Learning/

│

├── notebook/

│   └── transfer\_learning.ipynb

│

├── .gitignore

├── README.md

└── dataset/              # Not included in GitHub

```



\## 🚀 How to Run



\### 1. Clone the repository



```bash

git clone https://github.com/saadahmadl682-hue/InceptionV3-Transfer-Learning.git

```



\### 2. Create a virtual environment



```bash

python -m venv venv

```



\### 3. Activate the virtual environment



\*\*Windows PowerShell:\*\*



```powershell

.\\venv\\Scripts\\Activate.ps1

```



\### 4. Install dependencies



```bash

pip install tensorflow numpy pandas matplotlib jupyter

```



\### 5. Add the dataset



Place the scene classification dataset inside the project directory using the dataset structure expected by the notebook.



\### 6. Open the notebook



```bash

jupyter notebook

```



Open:



```text

notebook/transfer\_learning.ipynb

```



and run the cells.



\## 📌 Model File



The trained `.keras` model is not included in this repository because of its large file size.



The notebook contains the complete model training and evaluation workflow, allowing the model to be recreated.



\## 🎯 Learning Objectives



This project demonstrates practical experience with:



\* Transfer Learning

\* Convolutional Neural Networks

\* Image Classification

\* InceptionV3

\* Model Evaluation

\* Training and Validation

\* TensorFlow/Keras

\* Computer Vision



\## 👨‍💻 Author



\*\*Saad Ahmad Malik\*\*



BS Computer Science

University of Central Punjab




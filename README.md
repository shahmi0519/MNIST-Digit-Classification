# ✍️ Handwritten Digits Classification using MNIST Dataset

This project demonstrates how to classify handwritten digits (0–9) using the MNIST dataset and a neural network built with TensorFlow/Keras. It includes model development from basic linear models to multi-layer dense networks, and final evaluation with confusion matrices.

---

## 📚 Dataset

- **Name:** MNIST Handwritten Digits
- **Samples:** 70,000 total (60,000 training + 10,000 testing)
- **Image Size:** 28x28 pixels (grayscale)
- **Classes:** Digits from 0 to 9

---

## 🧠 Models Implemented

| Version | Model Details                                           |
|---------|---------------------------------------------------------|
| v1      | No hidden layer (Single dense output layer)             |
| v2      | One hidden layer with 100 neurons (ReLU + Sigmoid)      |
| v3      | Used `Flatten()` layer to simplify architecture         |

---

## 🔍 Techniques Used

- Pixel Normalization [0-255] → [0-1]
- Reshaping with `.reshape()` and `Flatten()` layer
- Dense Neural Networks with `ReLU` and `Sigmoid`
- Accuracy and Confusion Matrix visualization

---

## ⚙️ Installation

1. Clone the repository:
  ```bash
  git clone https://github.com/shahmi0519/MNIST-Digit-Classification.git
  ```
2. Install dependencies:
  ```bash
  pip install -r requirements.txt
  ```
3. Run the notebook:
  ```bash
  jupyter notebook notebooks/mnist_digits_classification.ipynb
  ```

---

## 📂 Project Structure
```bash
mnist-digit-classification/
├── notebooks/
│   └── mnist_digits_classification.ipynb
├── requirements.txt
├── README.md
└── LICENSE 
```
----

## ✍️ Author
**Ahamed Shahmi A.J**
- **📧 Mail**: [`shahmiahamed0519@gmail.com`](mailto:shahmiahamed0519@gmail.com)
- **🔗 LinkedIn**: [`Ahamed Shahmi`](https://www.linkedin.com/in/ahamed-shahmi-abduljabbar/)
- **💻 GitHub**: [`shahmi0519`](https://github.com/shahmi0519)
---

## 📝 License
This project is licensed under the MIT License – see the LICENSE file for details.

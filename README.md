## Car Driver Distraction Detection 🚗💻

Welcome to the **Car Driver Distraction Detection** project. This project focuses on detecting distracted driving behaviors using machine learning and image processing techniques. The goal is to reduce road accidents caused by distracted driving by identifying and classifying various driver behaviors in real-time.

---

## 📋 Overview

Distracted driving is one of the leading causes of road accidents worldwide. This project aims to address this issue by developing a machine learning model that can accurately detect and classify distracted driving behaviors using image data. The dataset includes multiple categories of distracted behaviors, enabling the model to precisely identify specific actions that may lead to accidents.

---

## 🛠️ Features

- **Image Preprocessing**: Efficient preprocessing techniques for clean and normalized image data, including resizing, normalization, and augmentation.
- **Model Training**: A robust machine learning model (e.g., CNN) trained to identify various driver behaviors with high accuracy.
- **Evaluation**: Comprehensive metrics (e.g., log loss, accuracy, precision, recall) and visualization tools (e.g., confusion matrix, ROC curves) for assessing the model's performance.

---

## 📁 Dataset

- **Total Images**: 22,424 
  - **Training Set**: 17,939 images 
  - **Test Set**: 4,485 images 

- **Classes:** The dataset includes 10 classes of driver behaviors:
   - **c0**: Normal driving
   - **c1**: Texting - right
   - **c2**: Talking on the phone - right
   - **c3**: Texting - left
   - **c4**: Talking on the phone - left
   - **c5**: Operating the radio
   - **c6**: Drinking
   - **c7**: Reaching behind
   - **c8**: Hair and makeup
   - **c9**: Talking to passenger
---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:
- Python 3.7+ 
- Jupyter Notebook 
- Required Python packages (see [requirements.txt](./requirements.txt)) 

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/wassim-bounaim/car-driver-distraction
   ```
2. Navigate to the project directory:
   ```bash
   cd car-driver-distraction
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## 🧑‍💻 Usage

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook distracted_driver_detection_python.ipynb
   ```
2. Run all cells to preprocess the data, train the model, and evaluate the results. 

3. The notebook includes detailed steps for:
      - Loading and preprocessing the dataset.
      - Building and training the machine learning model.
      - Evaluating the model's performance using metrics like log loss, accuracy, and confusion matrices.
      - Visualizing the results to understand the model's strengths and weaknesses.

---

## 📊 Results

The notebook includes detailed metrics and visualizations showcasing the model's performance across different classes of distractions. Key evaluation metrics include:
   - Accuracy: The percentage of correctly classified images.
   - Confusion Matrix: A visualization of the model's predictions versus the actual labels.

---

## License

This project is licensed under the MIT License.
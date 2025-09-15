# Pneumonia-Detection-Using-Deep-Learning-Models-With-Chest-X--rays
This project uses deep learning models like DenseNet201, ResNet50, and InceptionV3 to detect pneumonia from chest X-rays. Trained on 5,947 images, DenseNet201 achieved 97% accuracy. The system shows promise for accurate, AI-based diagnosis in medical imaging, especially in low-resource settings.


# Pneumonia Detection Using Deep Learning with Chest X-rays

This project presents an AI-powered approach to detect **pneumonia** from **chest X-ray images** using deep learning techniques. By leveraging **transfer learning** and **Convolutional Neural Networks (CNNs)**, the system aims to support early diagnosis, especially in low-resource medical environments.

## 🔍 Objective
To classify chest X-rays as **Normal** or **Pneumonia** using pre-trained deep learning models and evaluate their effectiveness.

## 📊 Dataset
- 5,947 chest X-ray images
- Two classes: Normal and Pneumonia
- Preprocessed with resizing and augmentation (rotation, scaling, translation)
- 80-20 train-test split

## 🧠 Models Used
The following models were fine-tuned using transfer learning:
- DenseNet201  
- EfficientNetB0  
- InceptionV3  
- ResNet50  
- AlexNet

Each model uses a sigmoid activation function for binary classification.

## 📈 Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- ROC Curve / AUC  
- Confusion Matrix

## 🏆 Results
| Model          | Accuracy |
|----------------|----------|
| DenseNet201    | 97%      |
| EfficientNetB0 | 96%      |
| InceptionV3    | 96%      |
| ResNet50       | 96%      |
| AlexNet        | 93%      |

**DenseNet201** delivered the highest performance across all metrics.

## 📦 Project Structure
📁 Pneumonia-Detection/
┣ 📄 README.md
┣ 📄 dlproject.ipynb
┣ 📁 models/
┗ 📁 data/


## ⚙️ Installation
Install dependencies using:

```bash
pip install -r requirements.txt
💡 Conclusion
Deep learning models, particularly DenseNet201, have shown strong potential for accurate pneumonia detection. With proper validation and deployment, such systems could aid real-time diagnosis in medical settings.

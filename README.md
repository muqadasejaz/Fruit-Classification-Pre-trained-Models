# 🍎 Fruit Classification (Multiclass) Using Pre-trained Models

A deep learning–based multiclass image classification system that uses pre-trained models (VGG16 and MobileNet) to accurately identify different fruit categories from images.

##  Kaggle Notebook

- **VGGNet Model (EDA + Training + Evaluation)**
- Notebook includes full pipeline: data preprocessing, visualization, training, and predictions
- **Kaggle Notebook:** [Fruit Classification Multiclass Problem](https://www.kaggle.com/code/muqaddasejaz/fruit-classification-multiclass-problem-vggnet16/notebook)

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📖 Project Overview

This project focuses on **multiclass fruit classification** using deep learning and transfer learning techniques. Pre-trained convolutional neural networks were used to classify images into 10 different fruit categories.

Two models were implemented:
- **VGGNet (VGG16)**
- **MobileNet**

Both models were trained on a Kaggle dataset using GPU acceleration for **100 epochs**, and their performance was evaluated using accuracy and loss metrics.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🎯 Objectives

- Build an accurate **multiclass image classification system**
- Apply **transfer learning** using pre-trained CNN models
- Perform **Exploratory Data Analysis (EDA)** on image dataset
- Compare performance of different architectures (VGG16 vs MobileNet)
- Evaluate model predictions on **test and unseen data**

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## ✨ Features

- Pre-trained model fine-tuning (VGG16, MobileNet)
- Image data preprocessing and augmentation
- Detailed **EDA (Exploratory Data Analysis)**
- Visualization of training images per class
- Training vs validation performance plots
- Predictions on unseen data
- Performance comparison between models

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🛠️ Tools & Technologies

- Python
- TensorFlow / Keras
- NumPy, Pandas
- Matplotlib, Seaborn
- OpenCV
- Kaggle GPU Environment

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📊 Dataset

- **Source:** https://www.kaggle.com/datasets/karimabdulnabi/fruit-classification10-class

### Classes:
- Apple
- Banana
- Avocado
- Cherry
- Kiwi
- Mango
- Orange
- Pineapple
- Strawberries
- Watermelon

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🔍 Exploratory Data Analysis (EDA)

### 📌 Training Images Visualization
- Sample images from dataset were visualized to understand:
  - Image quality
  - Class distribution
  - Variability across categories

  <img width="1433" height="1582" alt="image" src="https://github.com/user-attachments/assets/39f219b4-bd29-40a4-84ac-cbc929dffbad" />


### 📌 Per-Class Visualization
Each fruit class was explored individually:
- Apple

<img width="1291" height="290" alt="image" src="https://github.com/user-attachments/assets/f53450f1-630e-431a-a276-2a13e01496c0" />

- Banana

<img width="1282" height="290" alt="image" src="https://github.com/user-attachments/assets/46de7fa3-a8c3-47d2-b560-2b8a917cadf6" />

- Avocado

<img width="1407" height="290" alt="image" src="https://github.com/user-attachments/assets/673e47ec-72de-495b-8ed0-1f8d4d60d6fc" />

- Cherry

<img width="1319" height="290" alt="image" src="https://github.com/user-attachments/assets/76abba3f-58fb-48ee-a837-411b8e50975e" />

- Kiwi

<img width="1373" height="290" alt="image" src="https://github.com/user-attachments/assets/599a6f02-33ec-4262-aaa1-5372572f711c" />

- Mango

<img width="1372" height="290" alt="image" src="https://github.com/user-attachments/assets/69d120fd-e68c-43b1-8ba5-2f92518b2e5e" />

- Orange

<img width="1276" height="290" alt="image" src="https://github.com/user-attachments/assets/0c440f3c-f295-474a-9656-aa229c63dcc9" />

- Pineapple

<img width="1294" height="290" alt="image" src="https://github.com/user-attachments/assets/57515141-f2ce-42a1-b564-87b997baa4e6" />

- Strawberries

<img width="1336" height="290" alt="image" src="https://github.com/user-attachments/assets/708a0ce5-420b-44bd-83c1-01df49390fac" />

- Watermelon

<img width="1116" height="290" alt="image" src="https://github.com/user-attachments/assets/a1365b4f-9e8f-4a0a-b42b-bd6bdfe83fd3" />


----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🧠 Model Details

### 🔹 VGGNet (VGG16)
- Pre-trained on ImageNet
- Fine-tuned for 10-class classification
- Fully connected layers modified for classification

#### 📈 EDA & Analysis:
- Model architecture visualization

<img width="1261" height="4922" alt="image" src="https://github.com/user-attachments/assets/86e07576-0218-468f-9db6-a1eb9a14e004" />

- Training vs Validation Accuracy

<img width="547" height="414" alt="image" src="https://github.com/user-attachments/assets/cdd16f86-14cb-4c26-980c-e3e2797792ac" />


- Training vs Validation Loss

<img width="547" height="413" alt="image" src="https://github.com/user-attachments/assets/f5592d4d-e57e-4681-88aa-3117455ad0df" />

- Predictions on:
  - Test data
  - Unseen images

<img width="1369" height="989" alt="image" src="https://github.com/user-attachments/assets/604383d5-e973-4d68-921a-50139539b4ab" />


----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### 🔹 MobileNet
- Lightweight and efficient architecture
- Suitable for faster training and deployment

#### 📈 EDA & Analysis:
- Model architecture visualization

<img width="1183" height="4589" alt="image" src="https://github.com/user-attachments/assets/ac3cc095-a3d5-487a-835e-4e2a77ea0f82" />

- Training vs Validation Accuracy

<img width="547" height="413" alt="image" src="https://github.com/user-attachments/assets/6e4342cb-9198-4584-a8ae-cc506b548b72" />

- Training vs Validation Loss

<img width="547" height="413" alt="image" src="https://github.com/user-attachments/assets/c684151a-a073-4b90-a8cf-46d90c9042b2" />

- Predictions on:
  - Test data
  - Unseen images

  <img width="1369" height="989" alt="image" src="https://github.com/user-attachments/assets/ae5b16ef-7d70-4a33-a7cf-263450e397ef" />


----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📊 Model Performance

| Model       | Accuracy (%) |
|------------|-------------|
| VGGNet     | 86%         |
| MobileNet  | 96%         |

- **MobileNet outperformed VGGNet** in both accuracy and efficiency.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📈 Results & Predictions
- Models successfully classified fruit images with high accuracy.
- MobileNet demonstrated better generalization on unseen data.
- Visual predictions confirmed strong classification performance across all classes.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## ✅ Conclusion
- Transfer learning significantly improves performance on image classification tasks.
- MobileNet proved to be more efficient and accurate compared to VGG16.
- Proper EDA and visualization helped in better understanding the dataset.
- The system can be extended for real-world applications like:
  - Smart agriculture
  - Automated sorting systems
  - Retail inventory management

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📚 References
- Kaggle Dataset: https://www.kaggle.com/datasets/karimabdulnabi/fruit-classification10-class
- TensorFlow Documentation: https://www.tensorflow.org/
- Keras Applications: https://keras.io/api/applications/

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 👤 Author

Muqadas Ejaz

BS Computer Science (AI Specialization)

AI/ML Engineer

Kaggle Grand Master

Data Science & Gen AI 

📫 Connect with me on [LinkedIn](https://www.linkedin.com/in/muqadasejaz/)  

🌐 GitHub: [github.com/muqadasejaz](https://github.com/muqadasejaz)

📬 Kaggle: [Kaggle Profile](https://www.kaggle.com/muqaddasejaz) 

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📎 License

This project is open-source and available under the [MIT License](LICENSE).

⭐ If you find this project useful, don’t forget to star the repository!

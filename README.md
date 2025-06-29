# Smart-Sorting-Transfer-Learning-for-Identifying-Rotten-Fruits-and-Vegetables
A deep learning-based web application that detects whether fruits and vegetables are **Fresh** or **Rotten** using transfer learning (VGG16). Designed to improve sorting efficiency in agricultural and retail environments.

---

## 📌 Overview

Sorting fruits and vegetables manually is labor-intensive and often inaccurate.  
**Smart Sorting** automates this process using a computer vision model, enhancing food quality checks in:

- 🏭 Food processing plants  
- 🛒 Supermarkets  
- 🏠 Smart kitchens

This project was developed as part of a SmartInternz internship program.

---

## 🚀 Features

✅ Classifies images of fruits/vegetables as **Fresh** or **Rotten**  
✅ Built using **Transfer Learning** with the **VGG16** model  
✅ Real-time predictions via a Flask web application  
✅ Clean, responsive HTML/CSS frontend  
✅ Compatible with deployment platforms like **Render**

---

## 🧠 Model Details

| Attribute         | Value                          |
|------------------|---------------------------------|
| Model Architecture | VGG16 (Pre-trained on ImageNet) |
| Input Size         | 224x224x3                      |
| Dataset            | 28 Fruit/Vegetable Categories  |
| Labels             | Fresh / Rotten                 |
| Accuracy           | ~92% (Validation)              |
| Format             | `.h5` (Keras SavedModel)       |

---
##📂 Folder Structure

Smart-Sorting/
├── app.py # Flask backend
├── requirements.txt # Python dependencies
├── runtime.txt # Python version hint for Render
├── Procfile # Render start command
├── static/
│ └── uploads/ # Stores uploaded images
├── templates/
│ ├── index.html # Upload interface
│ └── result.html # Result display
├── Project Files/ # Additional resources (optional)
│ └── model_link.txt # Link to model if not stored in repo
├── README.md # You're reading it!
---
##2. Set Up Virtual Environment (Optional but Recommended)

python -m venv venv
venv\Scripts\activate       # On Windows

##3. Install Dependencies

pip install -r requirements.txt
--
##4. Download the Trained Model

Check the Project Files/model_link.txt for a Google Drive link to the model.
Place the model file as:

smart_sorting_model.h5
in the same folder as app.py.

##5. Run the Application

python app.py
Then open http://127.0.0.1:5000 in your browser.

📸 Screenshots
![image](https://github.com/user-attachments/assets/36f228ba-4114-4699-a9b5-21e27520ec83)![image](https://github.com/user-attachments/assets/edfada45-5629-4a6e-9384-6d735c69f2e8)![image](https://github.com/user-attachments/assets/a44ad666-2500-45f0-b4d4-9ee326710701)
##📦 Model Details

Based on VGG16 pretrained on ImageNet

Fine-tuned on a fruit & vegetable freshness dataset

Accuracy: ~92%

28 classes grouped as Fresh or Rotten
---
##✍️ Author

Naresh Konduru (@naresh3806)

Internship Project for SmartInternz





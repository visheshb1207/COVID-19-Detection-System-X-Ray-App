<h1 align='center'>
  🩻 X-Ray Detection App 
</h1>
   

A Flask-based web application that uses deep learning (TensorFlow) to detect and classify chest X-ray images into three categories:  

- **COVID-19**   
- **Pneumonia**  
- **Normal**  

The models are trained on a Kaggle dataset containing **25,000+ chest X-ray images**.  

---

## 🚀 Features  
- Upload chest X-ray images via a simple web interface.  
- Predicts disease category (COVID-19, Pneumonia, Lung Opacity, Normal).  
- Built with **Flask + TensorFlow**.  
- Deployable on **Render**.  

---

## 🧠 Dataset  
- Source: [Kaggle – Chest X-ray Dataset](https://www.kaggle.com/datasets/bachrr/covid-chest-xray)  
- Size: 25,000+ images  
- Preprocessing: resizing, normalization, augmentation  

---

## 🏗️ Tech Stack  
- **Backend:** Flask (Python)  
- **ML/DL Framework:** TensorFlow / Keras  
- **Frontend:** HTML, CSS, Bootstrap  
- **Deployment:** Render  
- **Visualization:** Matplotlib  

---

## ⚙️ Installation  

```bash
# Clone the repository
git clone https://github.com/your-username/xray-detection-app.git
cd xray-detection-app

# Create virtual environment
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

# Install dependencies
pip install -r requirements.txt

# Run Flask app
python app.py
```

---

## 📸 Screenshots

<img width="1800" height="943" alt="image" src="https://github.com/user-attachments/assets/7bcfcda0-db27-4b83-860c-0f31ff48fe2d" />


<img width="1800" height="947" alt="image" src="https://github.com/user-attachments/assets/6a96d9e4-8ff8-45f2-be25-4bd9f2c9c697" />

<img width="1800" height="954" alt="image" src="https://github.com/user-attachments/assets/5b9f2205-f3c5-4a08-9dc0-06f18a71ecd3" />

## 🔮 Future Improvements  

- Add Grad-CAM visualization for infected regions.  
- Expand disease categories.  
- Build a hospital dashboard version.  

---

## 🤝 Contributing  

Contributions are welcome! Fork the repo and open a pull request.  

---

## 📜 License  

This project is licensed under the **MIT License**. 
2025 @ Vishesh Bairwa


# 🐾 Multi-Class Animal Image Classification using MobileNetV2

This project implements a multi-class image classifier for 90 animal categories using **Transfer Learning** with **MobileNetV2**. The dataset is sourced from Kaggle and includes thousands of labeled animal images. The model is trained and evaluated using TensorFlow and Keras.
 
---

## 📂 Dataset

- **Source**: [Kaggle: 90 Animal Image Dataset](https://www.kaggle.com/datasets/saurabhshahane/animal-image-dataset90) 
- **Classes**: 90 animal categories
- **Format**: Directory of images grouped by class name   
 
---

## 📌 Features

- ✅ Transfer Learning with **MobileNetV2**
- 🧼 Image preprocessing and real-time augmentation with `ImageDataGenerator`
- 📊 Class distribution visualization
- 📈 Training performance plots
- 🔍 Confusion Matrix and Classification Report
- 💾 Model saving for deployment

---

## 🛠 Tech Stack

- Python
- TensorFlow / Keras
- NumPy, Matplotlib, Seaborn
- Jupyter Notebook

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/animal-classifier-mobilenetv2.git
   cd animal-classifier-mobilenetv2
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. (Optional) Download the dataset manually from Kaggle or ensure `kaggle.json` is configured.

4. Run the notebook:
   ```bash
   jupyter notebook Multi_Class_Animal_Classification_Updated.ipynb
   ```

---

## 🖼️ Sample Predictions

> Add output prediction images or sample classification results here.

---

## 📈 Results

- Final Validation Accuracy: _X%_ (update based on training)
- MobileNetV2 proves effective for lightweight and fast classification tasks.

---

## 📥 Model Export

The trained model is saved as:
```bash
animal_classifier_mobilenetv2.h5
```

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

---

## 📄 License

This project is licensed under the MIT License.

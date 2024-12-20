# **Analisis Perbandingan Kinerja Metode VGG16 dan MobileNetV2 Pada Klasifikasi Kepadatan Lalu Lintas**

![Traffic Image](https://www.geotab.com/CMS-Media-production/Blog/NA/_2018/July/traffic_congestion/blog-traffic-congestion-hero@2x.jpg)



## Kelompok 24 Deep Learning

- Aisyah Tiara Pratiwi - 121450074
- Lulu Christin Sihombing - 121450152
- Rizka Yustiana Zahra - 121450058
- Muhammad Fahrul Aditya - 121450156
- Meinisa - 121450076
- Erwan Arief - 121450062

---

## 📱**Tentang Proyek**

Proyek ini bertujuan untuk menganalisis dan membandingkan **kinerja dua arsitektur deep learning**, yaitu **VGG16** dan **MobileNetV2**, pada klasifikasi kepadatan lalu lintas berdasarkan gambar kamera jalan raya. Dataset mencakup gambar yang dikategorikan ke dalam lima kelas:
1. *Empty*
2. *Low*
3. *Medium*
4. *High*
5. *Traffic Jam*

Implementasi dilakukan untuk mengevaluasi akurasi, waktu komputasi, dan efisiensi model pada perangkat dengan sumber daya terbatas.

---

## 🎙 Data 

- **Sumber Dataset**: 
  - Dataset diambil dari berbagai sumber open data seperti **Kaggle** dan rekaman kamera lalu lintas.
  - Tautan dataset: [Download Dataset](https://www.kaggle.com/datasets/rahat52/traffic-density-singapore)

---

## 📂 Metode Pengumpulan Data

1. **Data Crawling**: 
   Mengambil data dari API kamera lalu lintas.
2. **Data Labeling**: 
   Setiap gambar diklasifikasikan ke dalam salah satu dari lima kategori kepadatan.

---

## 📊 Metode Deep Learning 

- **Model 1**: **VGG16**
- **Model 2**: **MobileNetV2**
- **Evaluasi Kinerja**: Menggunakan metrik seperti Accuracy & Loss Train & Val Split, Analyze Misclassications, Correlation Matrix

---

## 🧠 Model  
Model yang digunakan dalam eksperimen dapat diunduh melalui tautan berikut:  
- 🔗 **[Download Model VGG16](https://github.com/user-attachments/models/vgg16-traffic-classifier.keras)**  
- 🔗 **[Download Model MobileNetV2](https://github.com/user-attachments/models/mobilenetv2-traffic-classifier.keras)**

---

## 🖥 Bahasa Pemrograman & Library 
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat&logo=pandas&logoColor=white)  ![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)  ![Keras](https://img.shields.io/badge/-Keras-D00000?style=flat&logo=keras&logoColor=white)  ![OpenCV](https://img.shields.io/badge/-OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)  ![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557C?style=flat&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/-Seaborn-3776AB?style=flat&logo=python&logoColor=white)


---

## 📚Tahapan Preprocessing

1. **Rescale Nilai Piksel**
2. **Augmentasi Data**
3. **Target Size Penyesuaian**
4. **Pemisahan Dataset**
5. **Penanganan Ketidakseimbangan Kelas**
6. **Visualisasi Data**

---

## 📈 Hasil Perbandingan Model 

| Model         | Akurasi (%) | Ketepatan prediksi | Performa terbaik |
|---------------|-------------|--------------|-----------------------|
| VGG16         |     84    |     16/20     |          Kelas Empty, Medium, High, Traffic jam|
| MobileNetV2   |     81    |     15/20     |          Kelas Empty, Traffic jam          |

**Kesimpulan**: VGG16  memilliki akurasi tertinggi (84%), tetapi membutuhkan sumber daya lebih besar. Sedangkan MobileNetV2 memiliki akurasi 81%, namun lebih efisien dalam waktu dan memori.

---



## 📧 Kontak Tim Peneliti

- aisyah.121450074@student.itera.ac.id
- lulu.121450152@student.itera.ac.id
- rizka.121450058@student.itera.ac.id
- muhammad.121450156@student.itera.ac.id
- meinisa.121450076@student.itera.ac.id
- erwan.121450062@student.itera.ac.id



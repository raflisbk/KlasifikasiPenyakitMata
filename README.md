# **Klasifikasi Penyakit Mata Menggunakan GoogleNet dan MobileNetV3-Small**

Repositori ini berisi program untuk klasifikasi penyakit mata manusia menggunakan algoritma **GoogleNet** dan **MobileNetV3-Small**, dilengkapi dengan teknik **Squeeze-and-Excitation**. Proyek ini bertujuan untuk menganalisis dan membandingkan akurasi kedua model dalam mendeteksi dan mengklasifikasikan penyakit mata berdasarkan citra medis.

---

## **Fitur Utama**
- **Preprocessing Data:** 
  - Augmentasi citra untuk meningkatkan kualitas data latih.
  - Normalisasi piksel untuk mempercepat konvergensi model.
- **Arsitektur Model:** 
  - Implementasi GoogleNet dan MobileNetV3-Small dengan **Squeeze-and-Excitation** untuk meningkatkan performa model.
- **Optimasi:**
  - Menggunakan algoritma **Adam Optimizer** untuk pembaruan bobot model.
- **Evaluasi Model:**
  - Metrik evaluasi meliputi akurasi, presisi, recall, dan F1-score.
  - Visualisasi performa model dengan confusion matrix dan kurva ROC-AUC.

---
## Install Dependensi
```bash
pip install -r requirements.txt
```
## Hasil Kesimpulan
Model MobileNetV3-Small menunjukkan akurasi lebih tinggi pada dataset tertentu karena efisiensi parameter dan arsitektur yang ringan.
Model GoogleNet lebih unggul dalam beberapa kasus dengan data yang kompleks karena memiliki arsitektur yang lebih dalam.



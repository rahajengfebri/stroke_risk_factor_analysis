# 📊 Analisis Faktor Risiko Penyakit Stroke pada Pasien

## 📌 Overview Project
Project ini bertujuan untuk menganalisis faktor-faktor yang dapat meningkatkan risiko stroke berdasarkan data kesehatan pasien.

Analisis dilakukan menggunakan data pasien yang berisi informasi seperti usia, BMI (indeks massa tubuh), kadar gula darah, riwayat hipertensi, penyakit jantung, dan kebiasaan merokok.

Melalui analisis ini diharapkan dapat diperoleh insight yang membantu memahami faktor risiko stroke sehingga dapat mendukung upaya pencegahan dan edukasi kesehatan masyarakat.

---

## ❗ Problem Statement
Stroke merupakan salah satu penyebab kematian tertinggi di Indonesia.

Dengan menganalisis data pasien, kita dapat mengidentifikasi faktor-faktor yang meningkatkan risiko stroke. Insight dari analisis ini dapat membantu:

- Tenaga medis dalam melakukan deteksi dan pencegahan dini
- Rumah sakit dalam memahami pola risiko pasien
- Pemerintah dalam membuat program kesehatan yang lebih tepat sasaran
- Meningkatkan kesadaran masyarakat terhadap faktor risiko stroke

---

## ❓ Business Question
Beberapa pertanyaan yang ingin dijawab dalam analisis ini antara lain:

1. Apa saja faktor yang menyebabkan stroke?
2. Bagaimana perbandingan jumlah pasien stroke dan non-stroke?
3. Faktor apa saja yang tidak langsung menyebabkan stroke tetapi dapat meningkatkan risikonya?

---

## 📊 Dataset
Dataset yang digunakan berisi data kesehatan pasien dengan beberapa variabel penting, antara lain:

- Age (Usia)
- Gender (Jenis Kelamin)
- Hypertension (Hipertensi)
- Heart Disease (Penyakit Jantung)
- BMI (Indeks Massa Tubuh)
- Avg Glucose Level (Kadar Gula Darah)
- Smoking Status (Status Merokok)
- Stroke (Status Stroke: Ya / Tidak)

Dataset ini digunakan untuk melihat hubungan antara kondisi kesehatan pasien dengan kejadian stroke.

---

## 🔍 Insight dari Data

### 1. Distribusi Data
Sebagian besar pasien dalam dataset tidak mengalami stroke sehingga distribusi data bersifat tidak seimbang.

### 2. Faktor Usia
Kasus stroke lebih banyak ditemukan pada kelompok usia yang lebih tua sehingga usia menjadi salah satu faktor yang cukup kuat dalam meningkatkan risiko stroke.

### 3. BMI
Distribusi BMI pada pasien stroke dan non-stroke relatif mirip. Pada dataset ini BMI belum menunjukkan hubungan yang signifikan secara eksploratif terhadap stroke.

### 4. Kebiasaan Merokok
Merokok dapat meningkatkan risiko penyakit jantung dan hipertensi yang pada akhirnya dapat meningkatkan kemungkinan terjadinya stroke.

### 5. Kadar Gula Darah
Kadar gula darah yang tinggi dapat merusak pembuluh darah dan meningkatkan risiko penyakit jantung maupun hipertensi.

### 6. Gaya Hidup
Gaya hidup tidak sehat seperti pola makan tidak sehat, kurang aktivitas fisik, dan kebiasaan merokok dapat meningkatkan risiko penyakit kardiovaskular yang berkaitan dengan stroke.

---

## ⚠️ Insight Tambahan dari Data

### Kasus Langka
Terdapat kasus data yang cukup tidak biasa yaitu pasien berusia 5 tahun yang memiliki beberapa kondisi seperti:
- penyakit jantung
- hipertensi
- kadar gula darah tinggi
- BMI kategori overweight
- merokok
- mengalami stroke

Kasus ini kemungkinan merupakan anomali data atau kondisi medis yang sangat jarang terjadi.

### Inkonsistensi Data
Ditemukan beberapa inkonsistensi pada kolom **work_type**, antara lain:

- Pasien usia di atas 20 tahun termasuk kategori **children**
- Beberapa pasien usia di bawah 11 tahun termasuk kategori **pekerja**

Hal ini menunjukkan kemungkinan adanya kesalahan pencatatan data sehingga perlu dilakukan perbaikan pada data.

---

## 💡 Recommendation

### 1. Optimalisasi Program Pemeriksaan Kesehatan Lansia
Institusi kesehatan dapat meningkatkan efektivitas program pemeriksaan kesehatan melalui:
- peningkatan partisipasi lansia dalam pemeriksaan rutin
- pemantauan tekanan darah dan kadar gula darah secara berkala
- edukasi mengenai pencegahan stroke dan gaya hidup sehat

### 2. Edukasi Gaya Hidup Sehat
Program yang dapat dilakukan antara lain:
- kampanye berhenti merokok
- edukasi pola makan sehat
- peningkatan aktivitas fisik

### 3. Analisis Data Lebih Lanjut
Analisis selanjutnya dapat ditingkatkan dengan:
- menggunakan dataset yang lebih besar
- meningkatkan kualitas data
- memperbaiki kategori variabel seperti **work_type** agar lebih jelas dan konsisten

---

## 📊 Presentasi Project
Untuk melihat penjelasan lengkap dari project ini, silakan lihat slide presentasi berikut:

🔗 [Link PPT ]([MASUKKAN_LINK_PPT_DISINI](https://www.canva.com/design/DAHA_sPdf7Y/IIZOQRqWrtVza58qe5-zVg/edit?utm_content=DAHA_sPdf7Y&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton))

---

## 🛠 Tools yang Digunakan
- Python (Data Cleaning & Data Preparation)
- Power BI (Visualisasi dan Dashboard)
- DAX (Feature Engineering)

# 🏦 Klasterisasi Pelanggan Kredit dengan K-Means

Proyek ini bertujuan untuk melakukan segmentasi pelanggan kredit berdasarkan karakteristik seperti penghasilan, usia, jumlah pinjaman, dan perilaku pembayaran. Dengan menerapkan algoritma **K-Means Clustering**, pelanggan dikelompokkan ke dalam beberapa klaster yang memiliki kemiripan pola, sehingga memudahkan analisis risiko dan pengambilan keputusan bisnis.

## 🎯 Tujuan Proyek

- Mengelompokkan pelanggan berdasarkan profil keuangan dan perilaku pembayaran
- Mengidentifikasi kelompok pelanggan berisiko tinggi, menengah, dan rendah
- Mendukung strategi pemasaran dan manajemen risiko berbasis data

## ⚙️ Alur Proyek

1. **Pra-pemrosesan Data**
   - Pembersihan data
   - Normalisasi fitur numerik (seperti penghasilan, jumlah pinjaman)
   
2. **Penentuan Jumlah Klaster**
   - Menggunakan metode **Elbow** untuk menentukan nilai optimal _k_

3. **Penerapan K-Means Clustering**
   - Pengelompokan pelanggan ke dalam _k_ klaster berdasarkan centroid terdekat

4. **Visualisasi dan Analisis**
   - Visualisasi hasil klasterisasi menggunakan PCA dan plot sebar
   - Analisis karakteristik masing-masing klaster

## 🛠️ Teknologi yang Digunakan

- Python
- Jupyter Notebook
- Scikit-learn
- Pandas
- Matplotlib & Seaborn

## 📊 Output Proyek

- Klaster pelanggan berdasarkan kemiripan profil kredit
- Visualisasi klaster yang mempermudah interpretasi
- Insight untuk pengambilan keputusan di sektor keuangan atau perbankan

## 📌 Catatan

Proyek ini sangat relevan untuk perusahaan keuangan yang ingin memahami segmentasi pelanggannya lebih baik, serta meningkatkan strategi penawaran produk dan mitigasi risiko kredit.

---
## Hasil klustering
<img width="471" alt="hasil clustering" src="https://github.com/user-attachments/assets/800f91dd-5c80-4428-8812-17c82a73ef84" />

dari garfik kita dapat menyimpulkan bahwa:


Klaster 0 cenderung menjadi pelanggan dengan perilaku konservatif, menggunakan batas kredit mereka dengan hati-hati dan jarang melakukan pembayaran penuh.

Klaster 1 mencakup pelanggan dengan pendapatan yang lebih tinggi, memiliki saldo yang lebih besar, melakukan pembelian yang lebih sering, dan lebih cenderung untuk membayar penuh.

Klaster 2 berisi pelanggan dengan profil keuangan yang lebih rentan, memiliki saldo dan batas kredit yang rendah, dan melakukan pembelian dengan frekuensi yang lebih rendah.

Untuk selengkapnya dapat dicek pada file Klustering_customer.ipynb


© 2024 – Proyek Klasterisasi Kredit oleh Tazkia Damayanti

# 🧠 Proyek Klasifikasi Penyakit Mata Berdasarkan Gambar Retina
Proyek ini merupakan bagian dari pemenuhan tugas modul Pengembangan Machine Learning, Saya mengambil contoh studi kasus dimana modeling ini nantinya digunakan untuk
mengklasifikasikan penyakit mata yang diambil dari dataset kaggle 'https://www.kaggle.com/datasets/gunavenkatdoddi/eye-diseases-classification'.

## 🩺 Deskripsi Dataset

Dataset ini terdiri dari gambar retina manusia yang diklasifikasikan ke dalam empat kategori:
- **Katarak**
- **Glaukoma**
- **Retinopati**
- **Normal**

Tujuan dari proyek ini adalah membangun model klasifikasi berbasis CNN (Convolutional Neural Network) untuk mengidentifikasi jenis penyakit berdasarkan citra retina.

---

## 📁 Isi Notebook

a. **Import Library**  
   - Inisiasi seluruh dependensi dan library yang digunakan, seperti TensorFlow, NumPy, Matplotlib, dll.

b. **Eksplorasi Dataset**  
   - Pemeriksaan struktur dataset.  
   - Visualisasi distribusi jumlah gambar untuk setiap label/kategori.

c. **Preprocessing**  
   - Resize gambar ke dimensi tertentu.  

   - Pembagian dataset menjadi tiga bagian: **train**, **validation**, dan **test**.

d. **Pembuatan dan Pelatihan Model**  
   - Membangun model CNN sederhana dengan 32 neuron pada layer awal.  
   - Pelatihan model menggunakan data latih dan validasi.

e. **Evaluasi Model**  
   - Evaluasi performa model menggunakan data uji.  
   - Menampilkan akurasi dan loss, serta metrik tambahan jika diperlukan.

---

## ▶️ Cara Menjalankan Notebook
- Pastikan semua library dan dependensi yang akan digunakan sudah terpasang
- Jalankan kode di dalam sel notebook proyek ini
- Selalu cek kembali apakah path yang telah dibuat tersinkronasi dengan dataset dan folder yang tersedia

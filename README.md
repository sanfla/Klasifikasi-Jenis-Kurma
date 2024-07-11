# KNN Classifier untuk Dataset Ajwa atau Medjool

Repositori ini berisi Jupyter Notebook yang mengimplementasikan classifier K-Nearest Neighbors (KNN) pada dataset Ajwa atau Medjool. Dataset ini bersumber dari UCI Machine Learning Repository.

## Dataset

Dataset dapat ditemukan di UCI Machine Learning Repository pada tautan berikut:
[Ajwa atau Medjool Dataset](https://archive.ics.uci.edu/dataset/879/ajwa+or+medjool)

### Deskripsi

Dataset ini mencakup berbagai fitur dari kurma Ajwa dan Medjool, dengan tujuan untuk mengklasifikasikan mereka secara akurat. Fitur-fitur tersebut meliputi:

- Panjang Buah
- Panjang Biji Buah
- Diameter Buah
- Berat Buah
- Kalori
- Warna
- Jenis

### File

- `knn.ipynb`: Jupyter Notebook ini berisi implementasi classifier K-Nearest Neighbors menggunakan dataset tersebut.

## Persyaratan

Untuk menjalankan Jupyter Notebook ini, Anda perlu menginstal dependensi berikut:

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- scikit-learn
- matplotlib

Anda dapat menginstal dependensi ini menggunakan pip:

```bash
pip install pandas numpy scikit-learn matplotlib
```

## Penggunaan

1. Clone repositori ini ke komputer lokal Anda.
```bash
git clone https://github.com/sanfla/Klasifikasi-Jenis-Kurma
```

2. Masuk ke direktori repositori.
```bash
cd Klasifikasi-Jenis-Kurma
```

3. Buka Jupyter Notebook.
```bash
jupyter notebook knn.ipynb
```

4. Jalankan sel-sel notebook untuk mengeksekusi klasifikasi KNN pada dataset.

## Hasil

Notebook ini akan memandu Anda melalui proses pemuatan data, preprocessing, pelatihan model KNN, dan evaluasi kinerjanya. Visualisasi dan metrik kinerja akan disediakan untuk membantu Anda memahami akurasi dan efektivitas model.

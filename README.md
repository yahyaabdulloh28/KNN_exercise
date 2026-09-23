# 📊 Visualisasi Algoritma K-NN (K-Nearest Neighbors)

Selamat datang! Proyek sederhana ini bertujuan untuk membantu siapa saja (bahkan yang baru belajar *Data Science* atau *Machine Learning*) memahami bagaimana algoritma **K-Nearest Neighbors (K-NN)** membagi dan mengelompokkan data.

---

## 💡 Apa itu K-NN? (Penjelasan Sederhana)

Bayangkan Anda punya tetangga baru. Untuk menebak seperti apa sifat tetangga tersebut, Anda bisa melihat sifat **$K$ tetangga terdekatnya**. 
- Jika nilai **$K = 1$**, Anda hanya melihat 1 tetangga paling dekat.
- Jika nilai **$K = 5$**, Anda melihat 5 tetangga terdekat dan mengambil suara terbanyak (voting).

Dalam proyek ini, kita menggunakan data bunga (*Iris Dataset*) dan melihat bagaimana nilai $K$ yang berbeda bisa mengubah "garis batas" keputusan model komputer.

---

## 🛠️ Persiapan (Apa yang Perlu Diinstal?)

Sebelum menjalankan program ini, pastikan komputer Anda sudah terinstal Python dan beberapa modul pendukung. 

Buka terminal / command prompt, lalu ketik perintah berikut:

```bash
pip install numpy matplotlib scikit-learn
```

---

## 🚀 Cara Menjalankan Kode

1. Unduh atau salin kode Python yang ada di notebook ini.
2. Simpan dalam sebuah file, misalnya `app.py`.
3. Jalankan file tersebut melalui terminal/command prompt:
   ```bash
   python app.py
   ```
*(Jika Anda menggunakan **Google Colab** atau **Jupyter Notebook**, Anda tinggal menekan tombol **Play / Run** pada setiap kolom kode).*

---

## 📈 Apa Hasil yang Akan Anda Lihat?

Program ini akan menampilkan 4 grafik berbeda yang menunjukkan batas wilayah klasifikasi untuk nilai $K$ yang berbeda:

1. **$K = 1$**: Batas wilayah sangat detail dan sensitif (mudah terpengaruh oleh satu data saja).
2. **$K = 5$ & $K = 10$**: Batas wilayah mulai lebih mulus dan seimbang.
3. **$K = 20$**: Batas wilayah menjadi jauh lebih sederhana karena memperhitungkan banyak tetangga sekaligus.

---

🎉 *Semoga proyek kecil ini membantu Anda memahami konsep dasar Machine Learning dengan lebih mudah!*

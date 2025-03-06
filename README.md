# Praktikum_AI_Workflow

# Muhamad Saepul Rizal (2306142)

# Deskripsi
Proyek ini bertujuan untuk menganalisis data penjualan produk harian dan memprediksi kebutuhan restock menggunakan algoritma Decision Tree. Data yang digunakan mencakup informasi penjualan, stok, dan harga satuan produk. Model machine learning dilatih untuk menentukan apakah suatu produk perlu di-restock berdasarkan jumlah stok yang tersedia.

# Teknologi yang Digunakan:
1. Python
2. Pandas
3. Scikit-learn
4. Matplotlib
5. Google Colab

# Dataset
Tanggal: Tanggal transaksi
Produk: Nama produk
Jumlah Terjual: Kuantitas produk yang terjual
Stok: Sisa stok setelah transaksi
Harga Satuan: Harga per unit produk
Total Penjualan: Hasil perkalian jumlah terjual dengan harga satuan
Keuntungan: Selisih antara total penjualan dengan biaya modal (asumsi modal Rp10.000 per produk)

# Langkah-Langkah Implementasi
1. Membuat dan Menyimpan Data, Dataset dibuat dalam bentuk dictionary dan disimpan sebagai file CSV.
2. Membaca dan Mengolah Data
   Mengonversi kolom tanggal ke format datetime.
   Menambahkan kolom "Total Penjualan" dan "Keuntungan".
   Menampilkan 5 data pertama untuk verifikasi.
3. Pelatihan Model AI
   Menggunakan algoritma Decision Tree untuk memprediksi apakah stok suatu produk perlu di-restock.
   Memisahkan dataset menjadi training dan testing.
   Melatih model dan mengevaluasi akurasinya.
4. Prediksi Restock, Menggunakan model untuk memprediksi apakah stok suatu produk baru perlu diisi ulang.
5. Visualisasi Data, Menampilkan scatter plot hubungan antara jumlah terjual, stok, dan keuntungan.

# Cara Menjalankan Proyek
1. Pastikan Python dan dependensi berikut telah terinstal:
   pip install pandas scikit-learn matplotlib
2. Jalankan skrip Python utama di Google Colab atau lokal dengan langkah berikut:
   Buka file skrip Python di Google Colab atau editor Python lokal.
   Jalankan seluruh sel kode secara berurutan.
   Perhatikan output prediksi restock dan visualisasi data.
3. Analisis hasil prediksi dan visualisasi data untuk pengambilan keputusan restock produk.
4. 


# Analisis Data Penjualan K-Pop Photocard di Shopee

## Deskripsi

Project ini bertujuan untuk menganalisis data penjualan K-Pop Photocard di Shopee menggunakan Python dan library seperti Pandas, NumPy, Matplotlib, Seaborn, dan Mlxtend. Analisis ini mencakup eksplorasi data, pembersihan data, dan analisis market basket untuk mengidentifikasi pola pembelian dan kombinasi produk yang menarik.

## Dataset

Dataset yang digunakan dalam project ini berisi informasi tentang pesanan photocard K-Pop di Shopee, termasuk nama produk, variasi, harga, jumlah, metode pembayaran, dan informasi pembeli. Dataset ini disimpan dalam file Excel "Kelompok 5.xlsx - orders.csv".

## Langkah-langkah Analisis

1. **Data Understanding:** Memahami dataset dengan melihat informasi umum, 5 baris pertama, jumlah baris dan kolom, dan nama kolom.
2. **Data Cleaning:** Membersihkan data dengan menangani missing value dan data duplikat. Missing value di kolom 'Status Pembatalan/ Pengembalian' dihapus, sementara missing value di kolom 'Nama Variasi' dan 'Username (Pembeli)' diisi dengan nilai default. Data duplikat juga diidentifikasi dan dihapus.
3. **Exploratory Data Analysis (EDA):** Melakukan analisis eksplorasi untuk mendapatkan insight dari data, seperti metode pembayaran yang paling umum, distribusi pembeli berdasarkan kota/kabupaten dan provinsi, dan produk yang paling diminati.
4. **Market Basket Analysis:** Menerapkan algoritma Apriori dan association rules untuk mengidentifikasi kombinasi produk yang sering dibeli bersamaan. Analisis ini bertujuan untuk menemukan pola pembelian dan rekomendasi produk yang potensial.

## Hasil Analisis

* **Metode pembayaran yang paling umum:** COD (Cash on Delivery)
* **Provinsi dengan transaksi terbanyak:** DKI Jakarta
* **Produk yang paling diminati:** Jaehyun, Mark, dan variasi lainnya.
* **Kombinasi produk yang menarik:** Beberapa kombinasi produk dengan asosiasi yang kuat diidentifikasi, seperti Taeyong dan Jaemin terhadap Doyoung.

## Kesimpulan

Analisis ini memberikan wawasan berharga tentang penjualan K-Pop Photocard di Shopee, seperti preferensi pembeli, produk populer, dan kombinasi produk yang menarik. Informasi ini dapat digunakan untuk meningkatkan strategi penjualan, seperti rekomendasi produk yang lebih personal dan promosi yang lebih efektif.


## Library yang Digunakan

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Mlxtend


## Kontributor

* Nama anggota kelompok

## Catatan

* Project ini dibuat sebagai bagian dari tugas kuliah atau pembelajaran data science.
* Dataset yang digunakan mungkin tidak representatif untuk seluruh penjualan K-Pop Photocard di Shopee.

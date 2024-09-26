# **Latar Belakang**
Dalam dunia bisnis makanan cepat saji, khususnya dalam industri pizza, analisis data penjualan memainkan peran penting. Keberhasilan suatu restoran pizza tidak hanya bergantung pada kualitas makanan yang mereka sajikan, tetapi juga pada bagaimana mereka memahami dan merespon tren penjualan serta preferensi pelanggan. Untuk membantu restoran pizza tetap kompetitif, analisis data penjualan memainkan peran penting dalam memahami pola penjualan dan memaksimalkan pendapatan.

# **Table of Contents**
* order_id: Pengidentifikasi unik untuk setiap pesanan yang dilakukan oleh tabel
* order_details_id: Pengidentifikasi unik untuk setiap pizza yang dilakukan dalam setiap pesanan (pizza dengan jenis dan ukuran yang sama disimpan dalam baris yang sama, dan jumlahnya bertambah)
* pizza_id: Pengidentifikasi kunci unik yang menghubungkan pizza yang dipesan dengan detailnya, seperti ukuran dan harga
* quantity: Jumlah yang dipesan untuk setiap pizza dengan jenis dan ukuran yang sama
* order_date: Tanggal pesanan dilakukan (dimasukkan ke dalam sistem sebelum dimasak & disajikan)
* order_time: Waktu pesanan dilakukan (dimasukkan ke dalam sistem sebelum dimasak & disajikan)
* unit_price: Harga pizza dalam USD
* total_price: unit_price * kuantitas
* pizza_size: Ukuran pizza (Kecil, Sedang, Besar, X Besar, atau XX Besar)
* pizza_type: Pengidentifikasi kunci unik yang menghubungkan pizza yang dipesan dengan detailnya, seperti ukuran dan harga
* pizza_ingredients: bahan-bahan yang digunakan dalam pizza seperti yang ditampilkan di menu (semuanya berisi Keju Mozzarella, meskipun tidak disebutkan; dan semuanya berisi Saus Tomat, kecuali jika ada saus lain yang disebutkan)
* pizza_name: Nama pizza seperti yang ditampilkan di menu

# **Contents**
1. Total Orderan Berdasarkan Jam, Hari, dan Bulan
2. Pendapatan Hasil Penjualan Per Bulan
3. Penjualan Berdasarkan Ukuran Pizza
4. Penjualan Berdasarkan Kategori Pizza
5. Pizza Names and Prices
6. Jumlah Pesanan Per Bulan Berdasarkan Hari
7. Waktu Pesanan Berdasarkan Tanggal Pesanan
8. Distribusi Pendapatan Berdasarkan Kategori dan Ukuran Pizza

# **Result**
1. Restoran biasanya paling ramai saat jam makan siang, terutama antara pukul 12 hingga 13.
2. Jumlah pesanan meningkat terjadi pada hari Jumat.
3. Pendapatan hasil penjualan paling tinggi di bulan July
4. Penjualan pizza didominasi oleh ukuran L, yang menjadi ukuran paling populer di antara semua pilihan.
5. Pesanan berdasarkan kategori pizza menunjukkan bahwa pizza klasik umumnya lebih disukai.
6. Tomat, paprika merah, dan bawang merah biasanya ada di hampir semua jenis pizza.
7. Meskipun toko pizza ini buka pukul 9, jumlah pesanan pada pukul 9 hampir tidak ada.

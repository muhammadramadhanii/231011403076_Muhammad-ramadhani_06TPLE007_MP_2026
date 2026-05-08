SOAL 1

1. Halaman utama aplikasi workshop kampus dibuat menggunakan Scaffold sebagai kerangka utama, AppBar untuk menampilkan judul aplikasi, dan ListView agar daftar workshop dapat di-scroll jika data banyak. Setiap workshop ditampilkan menggunakan Card supaya informasi terlihat rapi dan mudah dibaca. Di dalam card digunakan Column untuk menyusun judul, tanggal, lokasi, kuota, dan tombol daftar secara vertikal. Widget ElevatedButton digunakan sebagai tombol pendaftaran agar pengguna dapat langsung melakukan aksi dengan mudah.

2. Alasan Pemilihan Widget
Mengapa menggunakan ListView?

Karena data workshop bisa banyak dan pengguna perlu melakukan scroll ke bawah. Jika menggunakan Column biasa, tampilan bisa overflow ketika data bertambah.

Mengapa menggunakan Card?

Karena Card membuat informasi tiap workshop terlihat terpisah dan lebih mudah dibaca dibanding semua informasi ditampilkan tanpa batas.

Mengapa menggunakan Column?

Karena informasi workshop ditampilkan secara vertikal dari atas ke bawah sehingga lebih terstruktur.

Mengapa menggunakan ElevatedButton?

Karena tombol daftar harus terlihat jelas dan mudah ditekan oleh pengguna.


3. Dua Kesalahan UI yang Ingin Dihindari
   Tampilan terlalu penuh

 Jika terlalu banyak informasi tanpa jarak, pengguna akan sulit membaca isi aplikasi. Solusinya adalah menggunakan padding dan card.
 Ukuran teks terlalu kecil

 Teks kecil membuat pengguna cepat lelah membaca. Solusinya menggunakan ukuran font yang cukup besar dan jelas.

4. Penjelasan Kenyamanan Baca (UX)

Agar tampilan nyaman dibaca, informasi dibuat sederhana dengan warna yang tidak berlebihan. Setiap workshop dipisahkan menggunakan card sehingga pengguna dapat fokus membaca satu informasi dalam satu waktu. Penggunaan jarak antar komponen membuat tampilan lebih rapi dan tidak membingungkan. Judul workshop dibuat lebih besar dan tebal agar mudah dikenali. Tombol daftar dibuat jelas supaya pengguna langsung mengetahui aksi yang harus dilakukan.

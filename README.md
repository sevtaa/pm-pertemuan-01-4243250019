# Tugas Rutin 1 — Flutter Hello World

## 1. Identitas Mahasiswa

- Nama: Sevta Simamora
- NIM: 4243250019
- Kelas: [PSIK 24C]
- Mata Kuliah: Pemrograman Mobile
- Tugas: Tugas Rutin 1

## 2. Deskripsi Aplikasi

Aplikasi ini dibuat menggunakan Flutter sebagai implementasi awal pengembangan aplikasi mobile. Aplikasi menampilkan teks Hello World, nama mahasiswa, NIM, dan kelas. Widget tambahan yang digunakan meliputi Icon, Card, dan ElevatedButton. Tombol dapat ditekan untuk menampilkan pesan SnackBar.

## 3. Versi Flutter

Versi Flutter yang digunakan adalah Flutter 3.47.7 dengan Dart 3.13.5.

### Screenshot Flutter Version

![Flutter Version](screenshots/flutter-version.png)

### Screenshot Flutter Doctor

![Flutter Doctor](screenshots/flutter-doctor.png)

## 4. Screenshot Aplikasi

![Aplikasi Flutter Hello World](screenshots/aplikasi.png)

## 5. Kendala dan Solusi

### Kendala 1: Perintah `code .` tidak dikenali

Solusi: Folder proyek dibuka melalui menu File → Open Folder di Visual Studio Code karena perintah `code` belum dikenali oleh PowerShell.

### Kendala 2: Browser gagal terhubung ke VM Service

Solusi: Aplikasi dijalankan kembali menggunakan `flutter run -d chrome`. Setelah layanan debug berhasil terhubung, aplikasi dapat dijalankan melalui Chrome.

## 6. Esai: Native, Hybrid, dan Cross-platform

Pengembangan aplikasi mobile dapat dilakukan melalui pendekatan Native, Hybrid, dan Cross-platform. Ketiganya memiliki karakteristik berbeda dalam teknologi, kinerja, dan pemeliharaan.

Native merupakan pendekatan pengembangan aplikasi khusus untuk satu sistem operasi menggunakan teknologi yang sesuai, seperti Kotlin untuk Android dan Swift untuk iOS. Pendekatan ini cocok untuk aplikasi perbankan yang membutuhkan integrasi biometrik, keamanan, dan performa optimal.

Hybrid menggabungkan teknologi web seperti HTML, CSS, dan JavaScript dengan pembungkus aplikasi agar dapat dijalankan pada perangkat mobile. Pendekatan ini cocok untuk aplikasi katalog produk yang sebagian besar menampilkan konten web.

Cross-platform memungkinkan pengembangan aplikasi untuk beberapa sistem operasi menggunakan sebagian besar kode yang sama. Flutter merupakan salah satu framework yang menggunakan bahasa Dart. Contoh penerapannya adalah aplikasi pendidikan yang perlu tersedia pada Android dan iOS tanpa mengembangkan seluruh kode secara terpisah.

Kesimpulannya, Native sesuai untuk kebutuhan khusus platform dan performa tinggi, Hybrid cocok untuk aplikasi berorientasi web, sedangkan Cross-platform efisien untuk pengembangan aplikasi pada berbagai platform. Pemilihan pendekatan harus mempertimbangkan kebutuhan, biaya, kompleksitas, dan kemampuan tim pengembang.

## 7. Pernyataan Penggunaan AI

AI digunakan sebagai alat bantu untuk memahami struktur kode Flutter, mempelajari widget, dan menyusun dokumentasi. Kode diperiksa dan diuji kembali selama proses pengerjaan. Penggunaan AI disesuaikan dengan ketentuan tugas dan proses pengerjaan yang sebenarnya.
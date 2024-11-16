Latihan2 - Riska Ariana 2210010057

# Penghitung Umur
Aplikasi Penghitung Umur adalah aplikasi berbasis Java Swing yang memungkinkan pengguna untuk menghitung umur mereka berdasarkan tanggal lahir yang dipilih. Selain itu, aplikasi ini juga menampilkan informasi tentang hari ulang tahun berikutnya dan peristiwa penting yang terjadi pada tanggal tersebut.

## Fitur
Hitung Umur: Menghitung umur secara detail (tahun, bulan, hari) berdasarkan tanggal lahir.

Hari Ulang Tahun Berikutnya: Menampilkan hari dan tanggal ulang tahun berikutnya dalam format bahasa Indonesia.

Peristiwa Penting: Menampilkan daftar peristiwa penting yang terjadi pada tanggal ulang tahun berikutnya menggunakan API eksternal.

## Teknologi yang Digunakan
Java Swing: Untuk antarmuka pengguna.

com.toedter.calendar.JDateChooser: Untuk memilih tanggal lahir.

Java HTTP Client: Untuk mengambil data dari API eksternal.

JSON Processing (org.json): Untuk memproses data dari API.

## Instalasi
Prasyarat:

JDK 8 atau yang lebih baru.
Library eksternal:
toedter-calendar untuk komponen JDateChooser.
Library JSON (org.json).
Clone Repository:

bash
Copy code
git clone <URL_REPOSITORY>
Tambahkan Library Eksternal: Pastikan library eksternal yang diperlukan telah diimpor ke proyek.

## Jalankan Proyek:

Buka proyek di IDE seperti NetBeans atau IntelliJ IDEA.
Jalankan kelas PenghitungUmurFrame.
Penggunaan
Pilih tanggal lahir menggunakan komponen kalender.
Klik tombol Hitung Umur untuk menghitung umur dan mendapatkan informasi tambahan.
Informasi seperti umur, hari ulang tahun berikutnya, dan peristiwa penting akan muncul di layar.
Catatan
Peristiwa penting diambil dari API eksternal. Pastikan Anda memiliki koneksi internet yang stabil.
Jika pengambilan data dari API gagal, aplikasi akan menampilkan pesan error.
Kontribusi
Jika Anda ingin berkontribusi pada proyek ini:

Fork repository ini.
Buat branch baru untuk fitur Anda.
Lakukan pull request ke branch utama.
Lisensi
Proyek ini dilisensikan di bawah MIT License.

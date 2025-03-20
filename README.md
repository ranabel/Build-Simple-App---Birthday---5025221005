# Happy Birthday App with Jetpack Compose


**Nama:** Nabilah Atika Rahma  
**NRP:** 5025221005  
**Kelas:** PPB G - Week 3

Proyek ini adalah aplikasi sederhana "Happy Birthday" yang dibangun menggunakan Jetpack Compose, toolkit UI modern untuk Android.

## Memulai

1.  **Buat Proyek Baru:**
    * Buka Android Studio.
    * Pilih "Create New Project".
    * Pilih template "Empty Activity".
    * Beri nama proyek "Happy Birthday".
    * Atur minimum SDK ke API 24 (Nougat).
    * Klik "Finish".

2.  **Jetpack Compose:**
    * Jetpack Compose adalah toolkit untuk membangun UI Android secara deklaratif menggunakan Kotlin.
    * Gunakan anotasi `@Composable` untuk mendefinisikan UI secara hierarkis dan dinamis.
    * Compose menyederhanakan pengembangan UI dengan kode yang lebih sedikit dan fitur seperti pratinjau langsung di Android Studio.

3.  **Design Pane:**
    * Gunakan "Design Pane" di Android Studio untuk melihat pratinjau UI tanpa menjalankan aplikasi.
    * Tambahkan anotasi `@Preview` pada fungsi composable untuk menampilkan pratinjau.
    * Ini memudahkan pengembangan dan penyesuaian tampilan.

4.  **Menambahkan Elemen Teks:**
    * Tambahkan elemen teks menggunakan komponen `Text` di dalam fungsi composable.
    * Buat fungsi untuk menampilkan pesan ulang tahun.
    * Atur teks, ukuran font, dan alignment sesuai kebutuhan.

5.  **Mengubah Ukuran Font:**
    * Atur ukuran font dengan properti `fontSize`.
    * Gunakan unit `sp` (scalable pixels) agar ukuran teks dapat menyesuaikan preferensi pengguna.

6.  **Menambahkan Elemen Teks Lainnya:**
    * Tambahkan elemen teks kedua, seperti tanda tangan atau nama pengirim.
    * Gunakan komponen `Text` lagi dan atur properti seperti `fontSize` dan `modifier` untuk penyesuaian tampilan.

7.  **Mengatur Tata Letak:**
    * Atur tata letak teks menggunakan `Column` untuk susunan vertikal atau `Row` untuk susunan horizontal.
    * Gunakan `Column` untuk menempatkan pesan ulang tahun di atas dan tanda tangan di bawah.
    * Tambahkan padding dan alignment untuk memperbaiki posisi.

8.  **Menambahkan Ucapan ke Aplikasi:**
    * Panggil fungsi composable di `MainActivity` untuk menampilkan UI saat aplikasi dijalankan.
    * Gunakan `Surface` untuk mengatur latar belakang dan warna tema.
    * Pastikan teks dan tata letak sudah sesuai dengan pratinjau.

Dengan langkah-langkah ini, Anda dapat membuat aplikasi "Happy Birthday" sederhana menggunakan Jetpack Compose, menyesuaikan tampilan, dan mengatur tata letak dengan mudah.

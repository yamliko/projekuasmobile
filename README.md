# 📸 Aplikasi Pemesanan Jasa Foto Prewedding

Aplikasi Android "Pemesanan Jasa Foto Prewedding" adalah solusi digital untuk memudahkan calon pengantin dalam memilih dan memesan layanan foto prewedding. Aplikasi ini memungkinkan pengguna untuk melihat daftar paket indoor dan outdoor, melakukan booking langsung, serta melihat hasil dokumentasi melalui galeri.

---

## 🛠️ Prasyarat

Pastikan Anda telah menginstal perangkat lunak berikut di komputer Anda sebelum melanjutkan:

- **Git**: Untuk mengunduh (clone) kode dari GitHub.
- **Android Studio**: IDE resmi untuk pengembangan aplikasi Android.
- **Java Development Kit (JDK)**: Diperlukan untuk menjalankan Gradle dan membangun proyek.

---

## ⚙️ Teknologi & Struktur Proyek

### Teknologi yang Digunakan

| Komponen     | Deskripsi                                                    |
|--------------|--------------------------------------------------------------|
| Bahasa       | Kotlin                                                       |
| SDK          | Android SDK + Android Gradle Plugin                          |
| Database     | Lokal (SQLite/Room – jika digunakan untuk menyimpan data)    |
| UI           | XML Layout + Material Design                                 |
| Fungsional   | Booking, Paket, Galeri, Kontak & Panduan Pemesanan           |

---

### Struktur File Penting

| File/Kelas                 | Deskripsi                                                                 |
|----------------------------|--------------------------------------------------------------------------|
| `MainActivity.kt`          | Halaman utama yang menampilkan navigasi awal pengguna                   |
| `PaketActivity.kt`         | Menampilkan daftar paket foto indoor dan outdoor                         |
| `FormBookingActivity.kt`   | Form untuk melakukan pemesanan jasa foto prewedding                      |
| `ContactActivity.kt`       | Menampilkan informasi kontak dan panduan pemesanan                       |
| `GalleryActivity.kt`       | Menampilkan galeri dokumentasi hasil prewedding                          |
| `/layout/*.xml`            | File desain UI untuk setiap halaman                                      |
| `/database/`               | (Opsional) Direktori berisi model dan pengelolaan database lokal         |

---

## 🚀 Panduan Instalasi (Developer)

Berikut langkah-langkah untuk menginstal dan menjalankan aplikasi:

1. **Kloning Repositori**

```bash
git clone https://github.com/username/PreweddingApp.git
Buka Proyek di Android Studio

Jalankan Android Studio

Pilih File → Open dan arahkan ke folder hasil clone

Sinkronisasi Gradle

Android Studio akan secara otomatis melakukan sinkronisasi proyek.

Pastikan koneksi internet stabil untuk mengunduh dependensi.

Konfigurasi SDK (Jika Diperlukan)

Jika terjadi kesalahan, pastikan local.properties sudah mengarah ke SDK:

ini
Copy
Edit
sdk.dir=C\:\\Users\\NamaUser\\AppData\\Local\\Android\\Sdk
Jalankan Aplikasi

Pilih perangkat target (emulator atau device fisik)

Klik ▶️ untuk menjalankan aplikasi

🧪 Fitur Aplikasi
✅ Tampilan Beranda yang ramah pengguna

📦 Halaman Paket: menampilkan paket indoor & outdoor

📝 Halaman Form Booking: untuk melakukan pemesanan langsung

📸 Galeri: dokumentasi hasil prewedding

☎️ Kontak & Panduan: memudahkan pengguna dalam melakukan pemesanan

👥 Kontributor
Yamliko Ashabul Kahfi (221001009)
Dody Priamitra (221001014)

📝 Catatan
Aplikasi menyimpan data secara lokal (offline).

Versi rilis awal bersifat basic dan dapat dikembangkan lebih lanjut (misalnya dengan backend online).

Untuk tutorial lebih lengkap, Anda bisa menambahkan dokumentasi dalam bentuk video atau PDF di folder proyek.

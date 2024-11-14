# Tugas01-AplikasiCekNomorGenap/Ganjil
 Tugas01-M. Rian Gunadi-2210010497
 
![gambar](https://github.com/user-attachments/assets/51d31441-21ba-4ea4-bf29-6e4396293772)

![gambar](https://github.com/user-attachments/assets/3001756c-abd8-4e67-9fbf-07ae03ba153e)

# Aplikasi Cek Nomor Genap/Ganjil dan Prima

Aplikasi ini memungkinkan pengguna untuk memasukkan angka dan memeriksa apakah angka tersebut **genap atau ganjil**, serta apakah angka tersebut merupakan **bilangan prima**. Aplikasi ini menggunakan Java Swing untuk antarmuka grafis.

## Fitur

- **Validasi Input**: Membatasi input hanya untuk angka menggunakan `KeyListener` dan menampilkan pesan peringatan jika input tidak valid.
- **FocusListener**: Membersihkan `JTextField` saat mendapatkan fokus agar pengguna bisa langsung memasukkan angka tanpa gangguan.
- **Cek Bilangan Genap/Ganjil**: Menentukan apakah angka yang dimasukkan adalah genap atau ganjil.
- **Cek Bilangan Prima**: Menentukan apakah angka yang dimasukkan adalah bilangan prima atau bukan.
- **Penggunaan JOptionPane**: Menampilkan hasil cek angka, serta pesan kesalahan atau peringatan dalam dialog.

## Cara Penggunaan

1. **Input Angka**: Masukkan angka pada kolom yang disediakan.
2. **Tekan Tombol "Cek"**: Klik tombol "Cek" untuk memeriksa apakah angka yang dimasukkan adalah genap atau ganjil, serta apakah bilangan tersebut prima.
3. **Lihat Hasil**: Hasil akan ditampilkan dalam bentuk dialog yang menunjukkan apakah angka tersebut genap/ganjil dan apakah bilangan tersebut prima atau bukan.

### Contoh Hasil:
- **Input**: `7`
  - **Hasil**: "Angka 7 adalah Ganjil dan merupakan bilangan prima"
  
- **Input**: `4`
  - **Hasil**: "Angka 4 adalah Genap dan bukan bilangan prima"

### Pesan Error:
- Jika input bukan angka atau kosong, aplikasi akan menampilkan pesan kesalahan menggunakan `JOptionPane`.

## Persyaratan Sistem

- **Java**: Versi 8 atau lebih tinggi.
- **IDE**: Disarankan menggunakan IDE seperti IntelliJ IDEA, Eclipse, atau NetBeans untuk menjalankan aplikasi ini.

## Langkah-langkah untuk Menjalankan Aplikasi

1. **Unduh atau Kloning Proyek**: Download atau kloning repositori ini ke komputer Anda.
2. **Buka di IDE**: Buka proyek ini menggunakan IDE pilihan Anda.
3. **Jalankan Aplikasi**: Setelah proyek dibuka, jalankan kelas `AplikasiCekNomor` sebagai aplikasi Java.
4. **Input dan Cek**: Masukkan angka di kolom input dan klik tombol "Cek" untuk melihat hasilnya.

## Struktur Proyek

- **AplikasiCekNomor.java**: Kelas utama yang berisi logika aplikasi dan antarmuka grafis.
- **initComponents()**: Metode untuk menginisialisasi komponen antarmuka pengguna.
- **setupInputValidation()**: Metode untuk membatasi input hanya angka menggunakan `KeyListener`.
- **setupFocusListener()**: Metode untuk membersihkan teks pada `JTextField` saat mendapatkan fokus.
- **cekGenapGanjil()**: Metode untuk memeriksa apakah angka genap atau ganjil dan apakah angka tersebut bilangan prima.
- **isPrima()**: Metode untuk mengecek apakah suatu angka adalah bilangan prima.

## Lisensi

Aplikasi ini dilisensikan di bawah **MIT License**.



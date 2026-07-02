# Logical View

## Penjelasan

Logical View menggambarkan hubungan antar komponen utama pada Aplikasi Pemesanan Tiket. Pengguna (Pelanggan) berinteraksi dengan aplikasi untuk melakukan login, melihat daftar tiket, memilih jadwal, memesan tiket, melakukan pembayaran, dan melihat riwayat pemesanan. Setiap proses tersebut akan mengakses database untuk mengambil maupun menyimpan data.

## Komponen

- **Pelanggan**: Pengguna yang menggunakan aplikasi untuk memesan tiket.
- **Login**: Memverifikasi akun pengguna sebelum menggunakan layanan.
- **Kelola Tiket**: Menampilkan daftar tiket dan jadwal yang tersedia.
- **Pemesanan**: Memproses pemilihan tiket dan menyimpan data pemesanan.
- **Pembayaran**: Memproses transaksi pembayaran pengguna.
- **Riwayat**: Menampilkan daftar pemesanan yang pernah dilakukan.
- **Database**: Menyimpan data pengguna, tiket, pemesanan, pembayaran, dan riwayat transaksi.

## Diagram

<img width="624" height="282" alt="image" src="https://github.com/user-attachments/assets/a01ffd2e-496e-408e-bff6-f940b72babe5" />


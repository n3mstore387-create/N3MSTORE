# N3MSTORE Android app

Aplikasi Flutter N3MSTORE dengan halaman Home, Feed, Layanan, Pesanan, dan Profil. Tampilan hitam-putih.

## Build APK melalui GitHub Actions
1. Buat repository GitHub bernama `N3MSTORE`.
2. Upload **isi folder project ini** ke root repository (file `pubspec.yaml` harus terlihat langsung di halaman utama repository; jangan upload folder pembungkusnya).
3. Buka tab **Actions**, pilih workflow **Build N3MSTORE APK**, lalu klik **Run workflow** jika belum berjalan otomatis.
4. Setelah selesai berstatus hijau, buka hasil run dan unduh artifact **N3MSTORE-APK**. Ekstrak ZIP artifact, lalu install `app-release.apk` di Android.

## Fitur
- Home berisi kategori dan harga.
- Feed berisi informasi harga, pembayaran, dan ketentuan.
- Pemesanan layanan TikTok dengan kalkulasi harga.
- Informasi pembayaran DANA dan QRIS, termasuk gambar QRIS.
- Tombol WhatsApp untuk mengirim detail order ke admin.
- Riwayat pesanan lokal selama aplikasi tetap berjalan.

## Harga dasar per 100
- Followers Rp17.000
- Likes Rp5.000
- Saves Rp5.000
- Views Rp10.000
- Comments Rp20.000
- Shares Rp2.000

## Catatan penting
Versi ini adalah aplikasi pemesanan sederhana yang mengirim detail pesanan ke WhatsApp admin. Riwayat pesanan hanya tersimpan sementara di sesi aplikasi, belum menggunakan database online/admin dashboard. Pembayaran diverifikasi manual oleh admin. Pastikan QRIS dan rekening/nomor pembayaran masih benar sebelum dipublikasikan.

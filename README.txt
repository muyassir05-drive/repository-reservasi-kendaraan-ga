# Transcosmos Car Reservation System — Prototype

## Cara menjalankan
1. Ekstrak ZIP.
2. Buka folder `transcosmos_car_reservation_demo`.
3. Klik dua kali `index.html` (Chrome/Edge disarankan).

## Akun demo
- Karyawan — Laras: Login `2230332`
- Superior Karyawan — Rizal: Login `2220235`
- Admin GA: Login `2190482`
- Password semua akun: `TCID2026!`

## Fitur prototype
- Login berdasarkan role.
- Karyawan dapat mengajukan mobil operasional, Bluebird, dan Grab.
- Validasi bentrok jadwal dan aturan Ganjil Genap Jakarta.
- Site Jakarta, Semarang, Yogyakarta, Bali.
- Bluebird/Grab mewajibkan Jobcode, nominal, dan foto voucher.
- Superior dapat approve/reject permintaan Bluebird/Grab.
- Admin GA memonitor seluruh permintaan dan mengunduh laporan CSV yang dapat dibuka di Excel.
- Data tersimpan pada localStorage browser yang digunakan.

## Batasan penting
Ini adalah prototype front-end untuk uji alur, bukan sistem produksi. Akun/password demo tertanam di file, data hanya tersimpan pada browser/perangkat yang sama, belum ada database/server, sinkronisasi antar akun/perangkat, RLS, atau autentikasi aman. Foto bukti disimpan lokal pada browser. Jangan gunakan data pribadi/transaksi riil. Sebelum dipakai operasional, perlu integrasi Supabase dan autentikasi server-side.

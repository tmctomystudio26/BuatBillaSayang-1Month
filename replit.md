# Website Ucapan Romantis

## Overview
Website ucapan berbasis HTML dengan fitur interaktif untuk menampilkan pesan romantis kepada seseorang yang spesial. Website ini memiliki desain yang indah dengan animasi dan beberapa tahapan interaktif.

## Fitur Utama
- **Halaman Envelope**: Tampilan amplop yang dapat dibuka dengan animasi
- **Halaman Password**: Sistem PIN 4 digit untuk membuka pesan (personalisasi dengan tanggal jadian)
- **Memory Game**: Game mencocokkan kartu dengan ikon hati
- **Pesan Akhir**: Tampilan pesan romantis dengan animasi dan stiker

## Struktur Proyek
```
.
├── index.html          # File utama website
├── server.py          # Python HTTP server untuk menjalankan website
└── .gitignore         # File gitignore untuk Python
```

## Teknologi
- HTML5
- CSS3 (dengan animasi dan backdrop filter)
- Vanilla JavaScript
- Python HTTP Server

## Cara Menjalankan
Website berjalan otomatis melalui workflow "Server" di port 5000.

## Kustomisasi
Untuk mengubah konten ucapan, edit bagian script di index.html:
- `pinPassword`: PIN untuk membuka pesan
- `txtPesanUtama`: Pesan utama yang ditampilkan
- `txtTambahan`: Pesan tambahan
- Memory game icons dapat diubah di array `kartu`
- Nomor WhatsApp untuk tombol "Balas": 6285122936027

## Cara Testing Website
Untuk memastikan website berfungsi dengan baik:
1. Klik tombol "Buka" pada envelope
2. Masukkan PIN yang benar (default: 1509)
3. Mainkan memory game dengan mencocokkan semua kartu
4. Lihat pesan akhir yang ditampilkan

## Catatan
- Website menggunakan resource eksternal (fonts, audio, images) dari CDN
- Jika ada resource yang tidak load, periksa koneksi internet
- Background image dan audio dapat diganti sesuai preferensi

## Last Updated
14 Oktober 2025

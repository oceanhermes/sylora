# Pemeriksaan perubahan ikon, 30 September 2026

Lingkup: penggantian ikon pada landing page dan aplikasi. Ini bukan audit seluruh produk atau pengujian transaksi blockchain.

- R-04 / R-31 PASS: ikon Lucide resmi disimpan lokal dengan lisensinya; alasan pemilihan bentuk dan ukuran tercatat di DESIGN.md bagian 7.
- R-03 PASS: pemeriksaan browser pada lebar 360px dan 1280px menunjukkan scrollWidth tidak melebihi viewport; enam kartu aksi dan navigasi tetap muat.
- R-23 / R-38 PASS: perubahan memakai ikon fungsi yang sudah ada, tidak menambah logo, avatar, statistik, atau klaim produk.
- R-25 PASS (navigasi yang diubah): warna cocoa #755d50 dan matcha-deep #3e7a52 di atas putih memberi kontras lebih dari 4.5:1; ikon mengikuti warna label.
- R-26 / R-35 PASS (interaksi yang diubah): menu HP membuka/menutup, tautan Action menu menuju bagian yang benar; enam kartu aksi memilih jenis yang sesuai; Home, Challenges, Action, Redeem, dan Profile berpindah tab; pilihan Follow membuka modal, Close menutupnya.
- R-32 PASS (navigasi yang diubah): tombol navigasi tetap dapat diaktifkan dengan Enter dan memiliki focus ring; tombol Close tetap memiliki nama aksesibel.
- R-33 PASS: perubahan ditulis langsung ke sumber HTML/CSS; tidak ada helper penggantian sumber yang ditambahkan ke proyek.
- Konsistensi PASS: 64 referensi ikon statis dan kartu dinamis cocok dengan 41 simbol pada sprite; seluruh skrip inline pada kedua halaman lolos pemeriksaan sintaks JavaScript.
- Liveliness PASS (lingkup ikon): ENERGY 2 / RHYTHM 2 / MOTION 1; ikon sesuai fungsi dan tema cream/matcha, ukuran menegaskan hierarki, tanpa animasi baru.

Keterbatasan preview: halaman menampilkan kegagalan koneksi kontrak/server. Pengiriman bukti dan transaksi tidak diuji, dan tidak ada transaksi yang dijalankan dalam pemeriksaan ini.

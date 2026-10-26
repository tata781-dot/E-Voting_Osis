# E-Voting OSIS — file GitHub Pages

## Upload / perbarui file
1. Unduh dan ekstrak ZIP ini.
2. Buka repositori https://github.com/tata781-dot/E-Voting-Osis
3. Pilih **Add file → Upload files**.
4. Unggah `index.html` dan `.nojekyll` langsung di folder utama repositori (root), bukan di dalam folder lain.
5. Klik **Commit changes**.
6. Buka **Settings → Pages**. Pastikan sumbernya `Deploy from a branch`, branch `main`, folder `/(root)`.
7. Buka tab **Actions** dan tunggu proses Pages selesai; perubahan dapat memerlukan beberapa menit.
8. Di Android, buka tautan situs lewat Chrome dalam mode samaran untuk menghindari cache lama.

Alamat situs: https://tata781-dot.github.io/E-Voting-Osis/

## Jika masih putih
- Pastikan `index.html` yang baru benar-benar menggantikan file lama (nama harus huruf kecil persis).
- Buka URL dengan tambahan `?v=2` untuk memaksa cache URL baru: https://tata781-dot.github.io/E-Voting-Osis/?v=2
- Jika masih kosong, kirim screenshot dan status tab **Actions** → workflow Pages. File ini menampilkan pemberitahuan bila ada error JavaScript yang tertangkap.

## Catatan penting
Versi GitHub Pages ini adalah situs statis. Data voting disimpan di penyimpanan browser perangkat masing-masing (`localStorage`) dan tidak tersinkron antar-HP. Password admin di HTML/JavaScript juga dapat dilihat orang yang membuka source. Untuk pemilihan resmi, gunakan backend dan database dengan autentikasi di server; jangan gunakan versi statis ini sebagai sistem pemungutan suara yang harus aman dan serentak.

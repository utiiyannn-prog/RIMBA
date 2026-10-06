# RIMBA Enumerator Tracker

Aplikasi web sederhana untuk membantu enumerator Koridor RIMBA mengelola responden, nomor kuesioner, dokumentasi foto, dan progres survei.

## Teknologi

- HTML
- CSS
- JavaScript vanilla
- Penyimpanan data lokal di browser
- GitHub Pages untuk hosting statis

## Menjalankan lokal

Buka `index.html` di browser. Untuk pengalaman yang lebih konsisten, jalankan melalui local web server.

## Deploy ke GitHub Pages

Repository ini sudah disiapkan sebagai static site. File `index.html` berada di root sehingga dapat digunakan sebagai entry file GitHub Pages. GitHub Pages mendukung publikasi file HTML/CSS/JavaScript langsung dari repository. Untuk deployment otomatis, workflow di `.github/workflows/pages.yml` akan menjalankan deployment setiap push ke branch `main`.

Catatan: data responden disimpan secara lokal di browser pada versi ini. Jangan memasukkan data sensitif ke repository atau membagikan repository berisi data pribadi.

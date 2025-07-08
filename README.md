# Aplikasi Manajemen Artikel dengan Vue.js

Project ini adalah aplikasi frontend sederhana untuk mengelola daftar artikel menggunakan framework **Vue.js 3**. Aplikasi ini terhubung ke backend API CodeIgniter 4 melalui HTTP (menggunakan Axios) untuk melakukan operasi CRUD (Create, Read, Update, Delete) pada data artikel.

## Fitur Utama
- **Menampilkan daftar artikel** dalam bentuk tabel.
- **Menambah artikel baru** melalui form modal.
- **Mengedit artikel** yang sudah ada.
- **Menghapus artikel** dengan konfirmasi.
- **Status artikel** dapat dipilih antara Draft dan Publish.

## Teknologi yang Digunakan
- [Vue.js 3](https://vuejs.org/) (CDN)
- [Axios](https://axios-http.com/) (CDN)
- HTML, CSS

## Struktur File
- `index.html` — Halaman utama aplikasi.
- `assets/js/app.js` — Script utama Vue.js untuk logika aplikasi.
- `assets/css/style.css` — Style untuk tampilan aplikasi.

## Cara Kerja Singkat
1. **Menampilkan Data:**
   - Data artikel diambil dari endpoint API `/post` dan ditampilkan dalam tabel.
2. **Menambah/Update Data:**
   - Form modal digunakan untuk menambah atau mengedit artikel. Data dikirim ke API menggunakan POST (tambah) atau PUT (update).
3. **Menghapus Data:**
   - Data dihapus dengan mengirim request DELETE ke endpoint API.
4. **Status Artikel:**
   - Status dapat dipilih (Draft/Publish) saat menambah atau mengedit artikel.


*Project ini dibuat untuk latihan pemrograman frontend menggunakan Vue.js dan integrasi dengan API.*

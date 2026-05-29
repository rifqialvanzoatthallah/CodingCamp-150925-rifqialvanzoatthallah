# Todo List App

### Rifqi Alvanzo Atthallah

---

## Overview

Todo List App adalah aplikasi web sederhana yang digunakan untuk mencatat dan mengelola aktivitas harian. Aplikasi ini dibangun menggunakan HTML, CSS, dan JavaScript tanpa framework, dengan memanfaatkan Local Storage sebagai media penyimpanan data.

Project ini menekankan pada pemahaman dasar pengolahan data di sisi client serta manipulasi DOM secara dinamis.

---

## Tujuan Project

* Memahami dasar JavaScript (DOM manipulation)
* Mengimplementasikan Local Storage
* Membuat aplikasi interaktif berbasis web
* Melatih penulisan kode yang terstruktur

---

## Teknologi yang Digunakan

* HTML5
* CSS3
* JavaScript (Vanilla JS)
* Local Storage

---

## Fitur

* Menambahkan task baru beserta tanggal
* Menandai task sebagai selesai
* Menghapus task secara individu
* Menghapus seluruh task
* Filter task (All, Pending, Complete)
* Penyimpanan data otomatis di browser

---

## Struktur Project

```
todo-list-app/
│
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
```

---

## Cara Kerja

Data task disimpan dalam array dan akan disinkronkan ke Local Storage setiap terjadi perubahan. Saat halaman dimuat, data akan diambil kembali dari Local Storage dan ditampilkan ke dalam tabel.

Filtering dilakukan dengan memanfaatkan method `filter()` pada array, sedangkan rendering tampilan menggunakan manipulasi DOM secara langsung.

---

## Cara Menjalankan

1. Clone repository:

   ```
   git clone https://github.com/rifqialvanzoatthallah/CodingCamp-150925-rifqialvanzoatthallah.git
   ```

2. Masuk ke folder project:

   ```
   cd CodingCamp-150925-rifqialvanzoatthallah
   ```

3. Buka file `index.html` menggunakan browser

---

## Pengembangan Selanjutnya

* Fitur edit task
* Notifikasi deadline
* Tampilan responsive
* Mode gelap
* Integrasi database atau API

---

## Author

Rifqi Alvanzo Atthallah

---

## Penutup

Project ini merupakan bagian dari proses belajar dan akan terus dikembangkan seiring peningkatan kemampuan dalam pengembangan web.

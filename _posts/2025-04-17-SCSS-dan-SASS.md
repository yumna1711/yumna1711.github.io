---
layout: post
title: "SCSS DAN SASS"
---

SCSS dan SASS

SASS (Syntactically Awesome Stylesheets) adalah preprocessor CSS — artinya, ia memperluas fitur CSS biasa dengan menambahkan kemampuan seperti variabel, nesting (penulisan bersarang), fungsi, dan lainnya. SASS membantu menulis CSS yang lebih efisien, terstruktur, dan mudah dikelola. Pertama kali dikembangkan oleh Hampton Catlin dan Natalie Weizenbaum. Ditulis menggunakan bahasa Ruby (awalnya), tapi sekarang bisa dijalankan dengan berbagai tools modern (seperti Dart Sass).

SCSS (Sassy CSS) adalah sintaks baru dari SASS yang lebih mirip CSS. SCSS sebenarnya adalah format file dari SASS dengan ekstensi .scss, sedangkan SASS asli menggunakan ekstensi .sass.

File (.scss) atau (.sass) perlu dikompilasi menjadi file .(css) biasa agar bisa digunakan oleh browser.Tools seperti Dart Sass, Webpack, atau Node-sass digunakan untuk proses kompilasi ini.

Fungsi dan kegunaan SCSS/SASS
Menyimpan konfigurasi aplikasi atau sistem.
Digunakan untuk config file pada Jekyll (_config.yml) untuk mengatur:
Menggunakan variabel: untuk menyimpan warna, font, atau ukuran tertentu agar konsisten.
Nesting (penulisan bersarang): menyederhanakan penulisan selector yang kompleks.
Modularisasi kode: dengan @import atau @use, kamu bisa membagi file CSS menjadi bagian-bagian kecil.
Mixins dan functions: membuat blok kode yang dapat dipakai ulang, mirip fungsi dalam pemrograman.
Operasi matematika: bisa melakukan penjumlahan, pengurangan, dan perhitungan unit (px, em, %, dll).
Inheritance: menggunakan @extend untuk mewarisi properti dari selector lain.


![SCSS dan SASS](/assets/image/SCSS SASS.png)

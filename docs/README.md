# Simpelin CFI

## Introduction

Simpelin CSS Framework Invitation (CFI) adalah framework yang berfungsi untuk memudahkan anda dalam membuat website undangan tanpa perlu khawatir untuk menentukan struktur dari websitenya. CFI menyajikan styling ringan namun berkelas untuk mendukung pembuatan website anda.

Gabung bersama komunitas kami pada Discord untuk mendapatkan informasi terkini terkait dengan Simpelin CFI. Kunjungi halaman ini: https://discord.gg/pu7xv2jhQW

## Getting Started

Mulai pembuatan website anda menggunakan Simpelin CFI dengan mengimpornya melalui link CDN berikut:

**CSS**

```
https://cdn.jsdelivr.net/gh/simpelinCFI/simpelin@1.0.1/dist/css/style.min.css
```

**JS**

```
https://cdn.jsdelivr.net/gh/simpelinCFI/simpelin@1.0.1/dist/js/countdown.js
https://cdn.jsdelivr.net/gh/simpelinCFI/simpelin@1.0.1/dist/js/animation.js
https://cdn.jsdelivr.net/gh/simpelinCFI/simpelin@1.0.1/dist/js/video.js
https://cdn.jsdelivr.net/gh/simpelinCFI/simpelin@1.0.1/dist/js/music_envelope.js
https://cdn.jsdelivr.net/gh/simpelinCFI/simpelin@1.0.1/dist/js/slider.js
```

Untuk menggunakan video container, pastikan anda mengimpor CDN pendukung sebagaimana berikut:

```
https://code.jquery.com/jquery-3.6.1.min.js
https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css
https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200
fonts.googleapis.com/icon?family=Material+Icons
https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/js/all.min.js

```

## Quick Setup

Contoh Penggunaan dari CDN di atas dinyatakan pada file .html berikut. Anda dapat menyalin kode dibawah lalu menempelkan pada file html pada website anda.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link
      rel="stylesheet"
      href="https://cdn.jsdelivr.net/gh/simpelinCFI/simpelin@1.0.1/dist/css/style.min.css"
    />
    <title>Simpelin CFI</title>
    <link
      rel="icon"
      type="image/x-icon"
      href="https://simpelincfi.github.io/simpelin/asset_images/logo.png"
    />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css"
    />
    <link
      rel="stylesheet"
      href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200"
    />
    <link
      href="https://fonts.googleapis.com/icon?family=Material+Icons"
      rel="stylesheet"
    />
  </head>
  <body>
    <!-- Taruh body HTML anda disini... -->
  </body>
  <script src="https://code.jquery.com/jquery-3.6.1.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/js/all.min.js"></script>
  <script src="https://cdn.jsdelivr.net/gh/simpelinCFI/simpelin@1.0.1/dist/js/countdown.js"></script>
  <script src="https://cdn.jsdelivr.net/gh/simpelinCFI/simpelin@1.0.1/dist/js/animation.js"></script>
  <script src="https://cdn.jsdelivr.net/gh/simpelinCFI/simpelin@1.0.1/dist/js/video.js"></script>
  <script src="https://cdn.jsdelivr.net/gh/simpelinCFI/simpelin@1.0.1/dist/js/music_envelope.js"></script>
  <script src="https://cdn.jsdelivr.net/gh/simpelinCFI/simpelin@1.0.1/dist/js/slider.js"></script>
</html>
```

---
title: ColorTransformOperation enumeration
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/colortransformoperation/
---
## ColorTransformOperation enumeration

Mendefinisikan operasi transformasi warna.

Tipe ColorTransformOperation menampilkan anggota-anggota berikut:

## Bidang

| Bidang | Deskripsi |
| :- | :- |
| TINT | Menyemprotkan warna. Parameter berada dalam rentang antara 0 (warna asli) dan 1 (putih). |
| SHADE | Menyaring warna. Parameter berada dalam rentang antara 0 (warna asli) dan 1 (hitam). |
| COMPLEMENT | Mengubah warna menjadi warna komplementer RGB.<br/>            m = Max(r, g, b);<br/>            r = m - r;<br/>            g = m - g;<br/>            b = m - b; |
| INVERSE | Mengubah warna menjadi warna terbalik.<br/>            r = 1 - r;<br/>            g = 1 - g;<br/>            b = 1 - b; |
| GRAYSCALE | Mengubah warna menjadi abu-abu dengan kecerahan yang sama. Parameter diabaikan. |
| SET_ALPHA | Menentukan komponen alfa dari warna. Parameter berada dalam rentang antara 0 (transparan) dan 1 (opaque). |
| ADD_ALPHA | Menambahkan nilai parameter ke komponen alfa warna. Parameter berada dalam rentang antara -1 dan 1. |
| MULTIPLY_ALPHA | Mengalikan komponen alfa dengan nilai parameter. |
| SET_HUE | Mengubah komponen hue warna ke nilai parameter. Parameter berada dalam rentang antara 0 dan 360. |
| ADD_HUE | Menambahkan nilai parameter ke komponen hue warna. Parameter berada dalam rentang antara -360 dan 360. |
| MULTIPLY_HUE | Mengalikan komponen hue dengan nilai parameter. |
| SET_SATURATION | Mengubah komponen saturasi warna ke nilai parameter. Parameter berada dalam rentang antara 0 dan 1. |
| ADD_SATURATION | Menambahkan nilai parameter ke komponen saturasi warna. Parameter berada dalam rentang antara -1 dan 1. |
| MULTIPLY_SATURATION | Mengalikan komponen saturasi dengan nilai parameter. |
| SET_LUMINANCE | Mengubah komponen luminansi warna ke nilai parameter. Parameter berada dalam rentang antara 0 dan 1. |
| ADD_LUMINANCE | Menambahkan nilai parameter ke komponen luminansi warna. Parameter berada dalam rentang antara -1 dan 1. |
| MULTIPLY_LUMINANCE | Mengalikan komponen luminansi dengan nilai parameter. |
| SET_RED | Mengubah komponen merah warna ke nilai parameter. Parameter berada dalam rentang antara 0 dan 1. |
| ADD_RED | Menambahkan nilai parameter ke komponen merah warna. Parameter berada dalam rentang antara -1 dan 1. |
| MULTIPLY_RED | Mengalikan komponen merah dengan parameter. |
| SET_GREEN | Mengubah komponen hijau warna ke nilai parameter value. Parameter berada dalam rentang antara 0 dan 1. |
| ADD_GREEN | Menambahkan parameter ke komponen hijau warna. Parameter berada dalam rentang antara -1 dan 1. |
| MULTIPLY_GREEN | Mengalikan komponen hijau dengan nilai parameter. |
| SET_BLUE | Mengubah komponen biru warna ke nilai parameter. Parameter berada dalam rentang antara 0 dan 360. |
| ADD_BLUE | Menambahkan nilai parameter ke komponen biru warna. Parameter berada dalam rentang antara -1 dan 1. |
| MULTIPLY_BLUE | Mengalikan komponen biru dengan nilai parameter. |
| GAMMA | Koreksi gamma. Parameter diabaikan. |
| INVERSE_GAMMA | Koreksi gamma terbalik. Parameter diabaikan. |


### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)
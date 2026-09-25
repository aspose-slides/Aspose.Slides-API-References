---
title: Rectangle class
second_title: Aspose.Slides untuk Python via .NET Referensi API
description: Menyimpan sekumpulan empat integer yang mewakili lokasi dan ukuran sebuah persegi panjang.
type: docs
url: /id/aspose.slides/rectangle/
net_type: System.Drawing.Rectangle
---
## Rectangle kelas

Menyimpan sekumpulan empat integer yang mewakili lokasi dan ukuran sebuah persegi panjang. Kompatibel dengan .NET `System.Drawing.Rectangle`.

The Rectangle type exposes the following members:

## Konstruktor

| Constructor | Deskripsi |
| :- | :- |
| [`__init__(self, x=0, y=0, width=0, height=0)`](/slides/python-net/id/aspose.slides/rectangle/__init__/#int-int-int-int) | Membuat sebuah persegi panjang dengan lokasi dan ukuran yang ditentukan. Nilai float dipotong menjadi integer. |

## Properti

| Property | Deskripsi |
| :- | :- |
| [`x`](/slides/python-net/id/aspose.slides/rectangle/x/) | Mengambil koordinat x dari sudut kiri atas persegi panjang ini.<br/>            Read-only **int**. |
| [`y`](/slides/python-net/id/aspose.slides/rectangle/y/) | Mengambil koordinat y dari sudut kiri atas persegi panjang ini.<br/>            Read-only **int**. |
| [`width`](/slides/python-net/id/aspose.slides/rectangle/width/) | Mengambil lebar persegi panjang ini.<br/>            Read-only **int**. |
| [`height`](/slides/python-net/id/aspose.slides/rectangle/height/) | Mengambil tinggi persegi panjang ini.<br/>            Read-only **int**. |
| [`left`](/slides/python-net/id/aspose.slides/rectangle/left/) | Mengambil koordinat x dari tepi kiri persegi panjang ini. Equals to `x`.<br/>            Read-only **int**. |
| [`top`](/slides/python-net/id/aspose.slides/rectangle/top/) | Mengambil koordinat y dari tepi atas persegi panjang ini. Equals to `y`.<br/>            Read-only **int**. |
| [`right`](/slides/python-net/id/aspose.slides/rectangle/right/) | Mengambil koordinat x yang merupakan hasil penjumlahan `x` dan `width` dari persegi panjang ini.<br/>            Read-only **int**. |
| [`bottom`](/slides/python-net/id/aspose.slides/rectangle/bottom/) | Mengambil koordinat y yang merupakan hasil penjumlahan `y` dan `height` dari persegi panjang ini.<br/>            Read-only **int**. |
| [`is_empty`](/slides/python-net/id/aspose.slides/rectangle/is_empty/) | Menentukan apakah semua properti numerik dari persegi panjang ini memiliki nilai nol.<br/>            Read-only **bool**. |

## Metode

| Method | Deskripsi |
| :- | :- |
| [`contains(self, x, y)`](/slides/python-net/id/aspose.slides/rectangle/contains/#int-int) | Menentukan apakah titik yang ditentukan berada di dalam persegi panjang ini. |
| [`contains(self, point)`](/slides/python-net/id/aspose.slides/rectangle/contains/#point) | Menentukan apakah titik yang ditentukan berada di dalam persegi panjang ini. |
| [`contains(self, rect)`](/slides/python-net/id/aspose.slides/rectangle/contains/#rectangle) | Menentukan apakah wilayah persegi panjang yang direpresentasikan oleh `rect` sepenuhnya berada di dalam persegi panjang ini. |


### Catatan

Persegi panjang dibandingkan berdasarkan lokasi dan ukurannya dengan `==` serta dapat digunakan sebagai kunci kamus atau anggota set.


### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)
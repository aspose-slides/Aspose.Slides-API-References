---
title: RectangleF()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sebuah instance baru dari objek RectangleF yang mewakili sebuah persegi panjang dengan koordinat X dan Y serta nilai lebar dan tinggi diatur ke 0.
type: docs
weight: 1
url: /id/system.drawing/rectanglef/rectanglef/
---
## RectangleF::RectangleF() konstruktor


Membuat sebuah instance baru dari objek [RectangleF](../) yang mewakili sebuah persegi panjang dengan koordinat X dan Y serta nilai lebar dan tinggi diatur ke 0.

```cpp
System::Drawing::RectangleF::RectangleF()
```

## RectangleF::RectangleF(float, float, float, float) konstruktor


Membuat sebuah instance baru dari objek [RectangleF](../) yang mewakili sebuah persegi panjang dengan koordinat yang ditentukan dari sudut kiri atas serta lebar dan tinggi.

```cpp
System::Drawing::RectangleF::RectangleF(float x, float y, float width, float height)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | **float** | Nilai koordinat X dari sudut kiri atas persegi panjang |
| y | **float** | Nilai koordinat Y dari sudut kiri atas persegi panjang |
| width | **float** | Lebar persegi panjang |
| height | **float** | Tinggi persegi panjang |

## RectangleF::RectangleF(const PointF\&, const SizeF\&) konstruktor


Membuat sebuah instance baru dari objek [RectangleF](../) yang mewakili sebuah persegi panjang dengan koordinat sudut kiri atas yang ditentukan sebagai sebuah instance dari kelas [PointF](../../pointf/) dan lebar serta tinggi sebagai sebuah instance dari kelas [SizeF](../../sizef/).

```cpp
System::Drawing::RectangleF::RectangleF(const PointF &location, const SizeF &size)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| location | const [PointF](../../pointf/)\& | Menentukan lokasi sudut kiri atas persegi panjang |
| size | const [SizeF](../../sizef/)\& | Menentukan lebar dan tinggi persegi panjang |

## RectangleF::RectangleF(const Rectangle\&) konstruktor


Membuat sebuah instance baru dari objek [RectangleF](../) yang mewakili persegi panjang yang setara dengan yang ditentukan.

```cpp
System::Drawing::RectangleF::RectangleF(const Rectangle &rect)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Sebuah instance dari kelas [Rectangle](../../rectangle/) yang menentukan posisi dan ukuran persegi panjang yang akan direpresentasikan oleh objek yang sedang dibangun |

## Lihat Juga

* Kelas [RectangleF](../)
* Kelas [PointF](../../pointf/)
* Kelas [SizeF](../../sizef/)
* Kelas [Rectangle](../../rectangle/)
* Ruang Nama [System::Drawing](../../)
* Library [Aspose.Slides](../../../)
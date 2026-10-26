---
title: Inflate()
second_title: Referensi API Aspose.Slides untuk C++
description: Meningkatkan lebar dan tinggi persegi panjang yang diwakili oleh objek saat ini, sambil mempertahankan lokasi pusat geometris persegi panjang. Lebar dan tinggi ditingkatkan ke kedua arah sebesar jumlah yang ditentukan.
type: docs
weight: 261
url: /id/system.drawing/rectanglef/inflate/
---
## RectangleF::Inflate(float, float) metode


Meningkatkan lebar dan tinggi persegi panjang yang diwakili oleh objek saat ini, sambil mempertahankan lokasi pusat geometris persegi panjang. Lebar dan tinggi ditingkatkan ke kedua arah sebesar jumlah yang ditentukan.

```cpp
void System::Drawing::RectangleF::Inflate(float width, float height)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| width | **float** | Jumlah yang mana lebar persegi panjang akan ditingkatkan ke kedua arah |
| height | **float** | Jumlah yang mana tinggi persegi panjang akan ditingkatkan ke kedua arah |

## RectangleF::Inflate(const SizeF\&) metode


Meningkatkan lebar dan tinggi persegi panjang yang diwakili oleh objek saat ini, sambil mempertahankan lokasi pusat geometris persegi panjang. Lebar dan tinggi ditingkatkan ke kedua arah sebesar nilai lebar dan tinggi yang ditentukan oleh objek ukuran yang diberikan secara korespondensi.

```cpp
void System::Drawing::RectangleF::Inflate(const SizeF &size)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| size | const [SizeF](../../sizef/)\& | Objek [SizeF](../../sizef/) yang menentukan jumlah peningkatan lebar dan tinggi persegi panjang |

## RectangleF::Inflate(const RectangleF\&, float, float) metode


Meningkatkan lebar dan tinggi persegi panjang yang diwakili oleh objek yang ditentukan, sambil mempertahankan lokasi pusat geometris persegi panjang. Lebar dan tinggi ditingkatkan ke kedua arah sebesar jumlah yang ditentukan.

```cpp
static RectangleF System::Drawing::RectangleF::Inflate(const RectangleF &rect, float x, float y)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | const [RectangleF](../)\& | Sebuah persegi panjang yang akan diinflasi |
| x | **float** | Jumlah yang mana lebar persegi panjang akan ditingkatkan ke kedua arah |
| y | **float** | Jumlah yang mana tinggi persegi panjang akan ditingkatkan ke kedua arah |

### Nilai Kembalian

Objek [RectangleF](../) yang mewakili persegi panjang yang diperbesar

## Lihat Juga

* Kelas [RectangleF](../)
* Kelas [SizeF](../../sizef/)
* Ruang Nama [System::Drawing](../../)
* Pustaka [Aspose.Slides](../../../)
---
title: Inflate()
second_title: Referensi API Aspose.Slides untuk C++
description: Meningkatkan lebar dan tinggi persegi panjang yang diwakili oleh objek saat ini, sambil mempertahankan lokasi pusat geometris persegi panjang. Lebar dan tinggi ditambah pada kedua arah sesuai dengan jumlah yang ditentukan.
type: docs
weight: 261
url: /id/system.drawing/rectangle/inflate/
---
## Rectangle::Inflate(int, int) method


Meningkatkan lebar dan tinggi persegi panjang yang diwakili oleh objek saat ini, sambil mempertahankan lokasi pusat geometris persegi panjang. Lebar dan tinggi ditambah pada kedua arah sesuai dengan jumlah yang ditentukan.

```cpp
void System::Drawing::Rectangle::Inflate(int width, int height)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| width | int | Jumlah yang lebar persegi panjang akan ditambah pada kedua arah |
| height | int | Jumlah yang tinggi persegi panjang akan ditambah pada kedua arah |

## Rectangle::Inflate(const Size\&) method


Meningkatkan lebar dan tinggi persegi panjang yang diwakili oleh objek saat ini, sambil mempertahankan lokasi pusat geometris persegi panjang. Lebar dan tinggi ditambah pada kedua arah sesuai dengan nilai lebar dan tinggi dari objek size yang ditentukan.

```cpp
void System::Drawing::Rectangle::Inflate(const Size &size)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| size | const [Size](../../size/)\& | Objek [Size](../../size/) yang menentukan jumlah untuk meningkatkan lebar dan tinggi persegi panjang |

## Rectangle::Inflate(const Rectangle\&, int, int) method


Meningkatkan lebar dan tinggi persegi panjang yang diwakili oleh objek yang ditentukan, sambil mempertahankan lokasi pusat geometris persegi panjang. Lebar dan tinggi ditambah pada kedua arah sesuai dengan jumlah yang ditentukan.

```cpp
static Rectangle System::Drawing::Rectangle::Inflate(const Rectangle &rect, int x, int y)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | const [Rectangle](../)\& | Sebuah persegi panjang untuk diperbesar |
| x | int | Jumlah yang lebar persegi panjang akan ditambah pada kedua arah |
| y | int | Jumlah yang tinggi persegi panjang akan ditambah pada kedua arah |

### Nilai Kembalian

Objek [Rectangle](../) yang mewakili persegi panjang yang diperbesar

## Lihat Juga

* Kelas [Rectangle](../)
* Kelas [Size](../../size/)
* Ruang Nama [System::Drawing](../../)
* Pustaka [Aspose.Slides](../../../)
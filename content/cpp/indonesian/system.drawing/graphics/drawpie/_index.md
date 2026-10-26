---
title: DrawPie()
second_title: Referensi API Aspose.Slides untuk C++
description: Menggambar pai yang ditentukan menggunakan pen yang ditentukan pada permukaan yang diwakili oleh objek saat ini.
type: docs
weight: 261
url: /id/system.drawing/graphics/drawpie/
---
## Graphics::DrawPie(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) metode

Menggambar pai yang ditentukan menggunakan pen pada permukaan yang diwakili oleh objek saat ini.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, int32_t x, int32_t y, int32_t width, int32_t height, int32_t startAngle, int32_t sweepAngle)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Pen yang digunakan saat menggambar pai |
| x | **int32_t** | Koordinat X dari sudut kiri atas persegi panjang yang mendefinisikan elips |
| y | **int32_t** | Koordinat Y dari sudut kiri atas persegi panjang yang mendefinisikan elips |
| width | **int32_t** | Lebar persegi panjang yang mendefinisikan elips |
| height | **int32_t** | Tinggi persegi panjang yang mendefinisikan elips |
| startAngle | **int32_t** | Sudut dalam derajat yang diukur searah jarum jam dari sumbu X ke titik awal pai |
| sweepAngle | **int32_t** | Sudut dalam derajat yang diukur searah jarum jam dari **startAngle** ke titik akhir pai |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) metode

Menggambar pai yang ditentukan menggunakan pen pada permukaan yang diwakili oleh objek saat ini.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Pen yang digunakan saat menggambar pai |
| x | **float** | Koordinat X dari sudut kiri atas persegi panjang yang mendefinisikan elips |
| y | **float** | Koordinat Y dari sudut kiri atas persegi panjang yang mendefinisikan elips |
| width | **float** | Lebar persegi panjang yang mendefinisikan elips |
| height | **float** | Tinggi persegi panjang yang mendefinisikan elips |
| startAngle | **float** | Sudut dalam derajat yang diukur searah jarum jam dari sumbu X ke titik awal pai |
| sweepAngle | **float** | Sudut dalam derajat yang diukur searah jarum jam dari **startAngle** ke titik akhir pai |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, Rectangle, float, float) metode

Menggambar pai yang ditentukan menggunakan pen pada permukaan yang diwakili oleh objek saat ini.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, Rectangle rect, float startAngle, float sweepAngle)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Pen yang digunakan saat menggambar pai |
| rect | [Rectangle](../../rectangle/) | Persegi panjang yang mendefinisikan elips |
| startAngle | **float** | Sudut dalam derajat yang diukur searah jarum jam dari sumbu X ke titik awal pai |
| sweepAngle | **float** | Sudut dalam derajat yang diukur searah jarum jam dari **startAngle** ke titik akhir pai |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, RectangleF, float, float) metode

Menggambar pai yang ditentukan menggunakan pen pada permukaan yang diwakili oleh objek saat ini.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, RectangleF rect, float startAngle, float sweepAngle)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Pen yang digunakan saat menggambar pai |
| rect | [RectangleF](../../rectanglef/) | Persegi panjang yang mendefinisikan elips |
| startAngle | **float** | Sudut dalam derajat yang diukur searah jarum jam dari sumbu X ke titik awal pai |
| sweepAngle | **float** | Sudut dalam derajat yang diukur searah jarum jam dari **startAngle** ke titik akhir pai |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Pen](../../pen/)
* Kelas [Graphics](../)
* Kelas [Rectangle](../../rectangle/)
* Kelas [RectangleF](../../rectanglef/)
* Ruang Nama [System::Drawing](../../)
* Library [Aspose.Slides](../../../)
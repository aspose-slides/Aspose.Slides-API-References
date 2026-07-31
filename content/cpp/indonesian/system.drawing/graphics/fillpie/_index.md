---
title: FillPie()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengisi pai yang ditentukan menggunakan kuas yang ditentukan pada permukaan yang diwakili oleh objek saat ini.
type: docs
weight: 274
url: /id/system.drawing/graphics/fillpie/
---
## Graphics::FillPie(const SharedPtr\<Brush\>\&, int, int, int, int, int, int) metode

Mengisi pai yang ditentukan menggunakan kuas yang ditentukan pada permukaan yang diwakili oleh objek saat ini.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Kuas yang akan digunakan saat mengisi pai |
| x | int | Koordinat X sudut kiri atas persegi panjang yang mendefinisikan elips |
| y | int | Koordinat Y sudut kiri atas persegi panjang yang mendefinisikan elips |
| width | int | Lebar persegi panjang yang mendefinisikan elips |
| height | int | Tinggi persegi panjang yang mendefinisikan elips |
| startAngle | int | Sudut dalam derajat yang diukur searah jarum jam dari sumbu X ke titik awal pai |
| sweepAngle | int | Sudut dalam derajat yang diukur searah jarum jam dari **startAngle** ke titik akhir pai |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, float, float, float, float, float, float) metode

Mengisi pai yang ditentukan menggunakan kuas yang ditentukan pada permukaan yang diwakili oleh objek saat ini.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Kuas yang akan digunakan saat mengisi pai |
| x | **float** | Koordinat X sudut kiri atas persegi panjang yang mendefinisikan elips |
| y | **float** | Koordinat Y sudut kiri atas persegi panjang yang mendefinisikan elips |
| width | **float** | Lebar persegi panjang yang mendefinisikan elips |
| height | **float** | Tinggi persegi panjang yang mendefinisikan elips |
| startAngle | **float** | Sudut dalam derajat yang diukur searah jarum jam dari sumbu X ke titik awal pai |
| sweepAngle | **float** | Sudut dalam derajat yang diukur searah jarum jam dari **startAngle** ke titik akhir pai |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, Rectangle, float, float) metode

Mengisi pai yang ditentukan menggunakan kuas yang ditentukan pada permukaan yang diwakili oleh objek saat ini.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, Rectangle rect, float startAngle, float sweepAngle)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Kuas yang akan digunakan saat mengisi pai |
| rect | [Rectangle](../../rectangle/) | Persegi panjang yang mendefinisikan elips |
| startAngle | **float** | Sudut dalam derajat yang diukur searah jarum jam dari sumbu X ke titik awal pai |
| sweepAngle | **float** | Sudut dalam derajat yang diukur searah jarum jam dari **startAngle** ke titik akhir pai |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Brush](../../brush/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)
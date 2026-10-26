---
title: AddCurve()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan kurva yang ditentukan ke jalur yang diwakili oleh objek saat ini.
type: docs
weight: 274
url: /id/system.drawing.drawing2d/graphicspath/addcurve/
---
## GraphicsPath::AddCurve(const ArrayPtr\<PointF\>\&, float) metode

Menambahkan kurva yang ditentukan ke jalur yang diwakili oleh objek saat ini.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<PointF> &points, float tension=0.5)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | Titik-titik yang menentukan kurva |
| tension | **float** | Menentukan jumlah kelengkungan kurva di antara titik kontrol |

## GraphicsPath::AddCurve(const ArrayPtr\<Point\>\&, float) metode

Menambahkan kurva yang ditentukan ke jalur yang diwakili oleh objek saat ini.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<Point> &points, float tension=0.5)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | Titik-titik yang menentukan kurva |
| tension | **float** | Menentukan jumlah kelengkungan kurva di antara titik kontrol |

## GraphicsPath::AddCurve(const ArrayPtr\<PointF\>\&, int, int, float) metode

Menambahkan kurva yang ditentukan ke jalur yang diwakili oleh objek saat ini.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<PointF> &points, int offset, int number_of_segments, float tension)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | Titik-titik yang menentukan kurva |
| offset | int | Indeks titik dalam **points** yang digunakan sebagai titik awal kurva |
| number_of_segments | int | Jumlah segmen yang digunakan untuk menggambar kurva |
| tension | **float** | Menentukan jumlah kelengkungan kurva di antara titik kontrol |

## GraphicsPath::AddCurve(const ArrayPtr\<Point\>\&, int, int, float) metode

Menambahkan kurva yang ditentukan ke jalur yang diwakili oleh objek saat ini.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<Point> &points, int offset, int number_of_segments, float tension)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | Titik-titik yang menentukan kurva |
| offset | int | Indeks titik dalam **points** yang digunakan sebagai titik awal kurva |
| number_of_segments | int | Jumlah segmen yang digunakan untuk menggambar kurva |
| tension | **float** | Menentukan jumlah kelengkungan kurva di antara titik kontrol |

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [GraphicsPath](../)
* Class [Point](../../../system.drawing/point/)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)
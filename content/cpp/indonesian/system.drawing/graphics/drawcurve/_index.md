---
title: DrawCurve()
second_title: Referensi API Aspose.Slides untuk C++
description: Menggambar spline menggunakan pena yang ditentukan.
type: docs
weight: 794
url: /id/system.drawing/graphics/drawcurve/
---
## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float) metode

Menggambar spline menggunakan pena yang ditentukan.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Sebuah pen untuk digunakan saat menggambar spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) dari titik-titik yang menentukan spline |
| tension | **float** | Nilai yang menentukan ketegangan spline |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float) metode

Menggambar spline menggunakan pena yang ditentukan.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Sebuah pen untuk digunakan saat menggambar spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) dari titik-titik yang menentukan spline |
| tension | **float** | Nilai yang menentukan ketegangan spline |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, int32_t, int32_t, float) metode

Menggambar spline menggunakan pena yang ditentukan.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Sebuah pen untuk digunakan saat menggambar spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) dari titik-titik yang menentukan spline |
| offset | **int32_t** | Offset dari elemen pertama dalam array **points** |
| numberOfSegments | **int32_t** | Jumlah segmen yang akan dimasukkan ke dalam kurva |
| tension | **float** | Nilai yang menentukan ketegangan spline |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, int32_t, int32_t, float) metode

Menggambar spline menggunakan pena yang ditentukan.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Sebuah pen untuk digunakan saat menggambar spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) dari titik-titik yang menentukan spline |
| offset | **int32_t** | Offset dari elemen pertama dalam array **points** |
| numberOfSegments | **int32_t** | Jumlah segmen yang akan dimasukkan ke dalam kurva |
| tension | **float** | Nilai yang menentukan ketegangan spline |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [Pen](../../pen/)
* Kelas [Point](../../point/)
* Kelas [Graphics](../)
* Kelas [PointF](../../pointf/)
* Ruang Nama [System::Drawing](../../)
* Perpustakaan [Aspose.Slides](../../../)
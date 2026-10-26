---
title: Matrix()
second_title: Aspose.Slides untuk C++ Referensi API
description: Membuat instance baru dari kelas Matrix yang merepresentasikan matriks identitas.
type: docs
weight: 1
url: /id/system.drawing.drawing2d/matrix/matrix/
---
## Matrix::Matrix() konstruktor


Membuat sebuah instance baru dari kelas [Matrix](../) yang merepresentasikan matriks identitas.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix()
```

## Matrix::Matrix(float, float, float, float, float, float) konstruktor


Membuat sebuah instance baru dari kelas [Matrix](../) dan menginisialisasinya dengan nilai-nilai yang ditentukan.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(float m11, float m12, float m21, float m22, float dx, float dy)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| m11 | **float** | Nilai baris pertama kolom pertama |
| m12 | **float** | Nilai baris pertama kolom kedua |
| m21 | **float** | Nilai baris kedua kolom pertama |
| m22 | **float** | Nilai baris kedua kolom kedua |
| dx | **float** | Nilai baris ketiga kolom pertama |
| dy | **float** | Nilai baris ketiga kolom kedua |

## Matrix::Matrix(const Rectangle\&, const ArrayPtr\<Point\>\&) konstruktor


Membuat sebuah instance baru dari kelas [Matrix](../) untuk transformasi geometrik yang didefinisikan oleh persegi panjang dan array titik yang ditentukan.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const Rectangle &rect, const ArrayPtr<Point> &plgpts)
```

## Matrix::Matrix(const RectangleF\&, const ArrayPtr\<PointF\>\&) konstruktor


Membuat sebuah instance baru dari kelas [Matrix](../) untuk transformasi geometrik yang didefinisikan oleh persegi panjang dan array titik yang ditentukan.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const RectangleF &rect, const ArrayPtr<PointF> &plgpts)
```

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [Matrix](../)
* Kelas [Rectangle](../../../system.drawing/rectangle/)
* Kelas [Point](../../../system.drawing/point/)
* Kelas [RectangleF](../../../system.drawing/rectanglef/)
* Kelas [PointF](../../../system.drawing/pointf/)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)
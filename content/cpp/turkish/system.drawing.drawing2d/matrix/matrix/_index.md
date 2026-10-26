---
title: Matrix()
second_title: C++ için Aspose.Slides API Referansı
description: Bir kimlik matrisi temsil eden Matrix sınıfının yeni bir örneğini oluşturur.
type: docs
weight: 1
url: /tr/system.drawing.drawing2d/matrix/matrix/
---
## Matrix::Matrix() yapıcı

Kimlik matrisini temsil eden [Matrix](../) sınıfının yeni bir örneğini oluşturur.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix()
```

## Matrix::Matrix(float, float, float, float, float, float) yapıcı

[Matrix](../) sınıfının yeni bir örneğini oluşturur ve belirtilen değerlerle ilklendirir.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(float m11, float m12, float m21, float m22, float dx, float dy)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| m11 | **float** | 1. satır 1. sütunun değeri |
| m12 | **float** | 1. satır 2. sütunun değeri |
| m21 | **float** | 2. satır 1. sütunun değeri |
| m22 | **float** | 2. satır 2. sütunun değeri |
| dx | **float** | 3. satır 1. sütunun değeri |
| dy | **float** | 3. satır 2. sütunun değeri |

## Matrix::Matrix(const Rectangle\&, const ArrayPtr\<Point\>\&) yapıcı

Belirtilen dikdörtgen ve nokta dizisiyle tanımlanan geometrik dönüşüm için [Matrix](../) sınıfının yeni bir örneğini oluşturur.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const Rectangle &rect, const ArrayPtr<Point> &plgpts)
```

## Matrix::Matrix(const RectangleF\&, const ArrayPtr\<PointF\>\&) yapıcı

Belirtilen dikdörtgen ve nokta dizisiyle tanımlanan geometrik dönüşüm için [Matrix](../) sınıfının yeni bir örneğini oluşturur.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const RectangleF &rect, const ArrayPtr<PointF> &plgpts)
```

## İlgili

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [Matrix](../)
* Sınıf [Rectangle](../../../system.drawing/rectangle/)
* Sınıf [Point](../../../system.drawing/point/)
* Sınıf [RectangleF](../../../system.drawing/rectanglef/)
* Sınıf [PointF](../../../system.drawing/pointf/)
* İsim Uzayı [System::Drawing::Drawing2D](../../)
* Kütüphane [Aspose.Slides](../../../)
---
title: Matrix()
second_title: مرجع Aspose.Slides للـ C++ API
description: ينشئ نسخة جديدة من الفئة Matrix التي تمثل مصفوفة هوية.
type: docs
weight: 1
url: /ar/system.drawing.drawing2d/matrix/matrix/
---
## Matrix::Matrix() منشئ

ينشئ نسخة جديدة من الفئة [Matrix](../) التي تمثل مصفوفة هوية.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix()
```

## Matrix::Matrix(float, float, float, float, float, float) منشئ

ينشئ نسخة جديدة من الفئة [Matrix](../) ويُهيئها بالقيم المحددة.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(float m11, float m12, float m21, float m22, float dx, float dy)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| m11 | **float** | القيمة للصف الأول العمود الأول |
| m12 | **float** | القيمة للصف الأول العمود الثاني |
| m21 | **float** | القيمة للصف الثاني العمود الأول |
| m22 | **float** | القيمة للصف الثاني العمود الثاني |
| dx | **float** | القيمة للصف الثالث العمود الأول |
| dy | **float** | القيمة للصف الثالث العمود الثاني |

## Matrix::Matrix(const Rectangle\&, const ArrayPtr\<Point\>\&) منشئ

ينشئ نسخة جديدة من الفئة [Matrix](../) للتحول الهندسي المحدد بالمستطيل المحدد ومصفوفة النقاط.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const Rectangle &rect, const ArrayPtr<Point> &plgpts)
```

## Matrix::Matrix(const RectangleF\&, const ArrayPtr\<PointF\>\&) منشئ

ينشئ نسخة جديدة من الفئة [Matrix](../) للتحول الهندسي المحدد بالمستطيل المحدد ومصفوفة النقاط.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const RectangleF &rect, const ArrayPtr<PointF> &plgpts)
```

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* الفئة [Matrix](../)
* الفئة [Rectangle](../../../system.drawing/rectangle/)
* الفئة [Point](../../../system.drawing/point/)
* الفئة [RectangleF](../../../system.drawing/rectanglef/)
* الفئة [PointF](../../../system.drawing/pointf/)
* نطاق [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)
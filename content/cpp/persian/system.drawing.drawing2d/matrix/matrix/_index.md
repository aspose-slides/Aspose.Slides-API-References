---
title: Matrix()
second_title: مرجع API Aspose.Slides برای C++
description: یک نمونه جدید از کلاس Matrix ایجاد می‌کند که یک ماتریس هویت را نمایندگی می‌کند.
type: docs
weight: 1
url: /fa/system.drawing.drawing2d/matrix/matrix/
---
## Matrix::Matrix() سازنده

یک نمونه جدید از کلاس [Matrix](../) ایجاد می‌کند که یک ماتریس هویت را نمایندگی می‌کند.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix()
```

## Matrix::Matrix(float, float, float, float, float, float) سازنده

یک نمونه جدید از کلاس [Matrix](../) ایجاد می‌کند و آن را با مقادیر مشخص‌شده مقداردهی اولیه می‌نماید.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(float m11, float m12, float m21, float m22, float dx, float dy)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| m11 | **float** | مقدار سطر اول ستون اول |
| m12 | **float** | مقدار سطر اول ستون دوم |
| m21 | **float** | مقدار سطر دوم ستون اول |
| m22 | **float** | مقدار سطر دوم ستون دوم |
| dx | **float** | مقدار سطر سوم ستون اول |
| dy | **float** | مقدار سطر سوم ستون دوم |

## Matrix::Matrix(const Rectangle\&, const ArrayPtr\<Point\>\&) سازنده

یک نمونه جدید از کلاس [Matrix](../) برای تبدیل هندسی تعریف‌شده توسط مستطیل مشخص‌شده و آرایه‌ای از نقاط ایجاد می‌کند.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const Rectangle &rect, const ArrayPtr<Point> &plgpts)
```

## Matrix::Matrix(const RectangleF\&, const ArrayPtr\<PointF\>\&) سازنده

یک نمونه جدید از کلاس [Matrix](../) برای تبدیل هندسی تعریف‌شده توسط مستطیل مشخص‌شده و آرایه‌ای از نقاط ایجاد می‌کند.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const RectangleF &rect, const ArrayPtr<PointF> &plgpts)
```

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Matrix](../)
* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [Point](../../../system.drawing/point/)
* Class [RectangleF](../../../system.drawing/rectanglef/)
* Class [PointF](../../../system.drawing/pointf/)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)
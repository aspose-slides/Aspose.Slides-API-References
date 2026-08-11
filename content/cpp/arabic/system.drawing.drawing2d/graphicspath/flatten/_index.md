---
title: Flatten()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يقوم بتمهيد كل منحنى في المسار عن طريق تحويله إلى سلسلة من الخطوط المتصلة. يتم استخدام قيمة التسطح 0.25.
type: docs
weight: 391
url: /ar/system.drawing.drawing2d/graphicspath/flatten/
---
## GraphicsPath::Flatten() طريقة

يقوم بتمهيد كل منحنى في المسار عن طريق تحويلها إلى سلسلة من الخطوط المتصلة. يتم استخدام قيمة التسطح 0.25.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten()
```

## GraphicsPath::Flatten(const MatrixPtr\&) طريقة

يقوم بتمهيد كل منحنى في المسار عن طريق تحويلها إلى سلسلة من الخطوط المتصلة. يتم استخدام قيمة التسطح 0.25.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix)
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | مصفوفة التحويل لتطبيقها على المسار قبل التمهيد |

## GraphicsPath::Flatten(const MatrixPtr\&, float) طريقة

يقوم بتمهيد كل منحنى في المسار عن طريق تحويلها إلى سلسلة من الخطوط المتصلة.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix, float flatness)
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | مصفوفة التحويل لتطبيقها على المسار قبل التمهيد |
| flatness | **float** | يحدد الحد الأقصى للخطأ المسموح به بين المنحنى وتقريبه الممهد |

## انظر أيضا

* Typedef [MatrixPtr](../../matrixptr/)
* الفئة [GraphicsPath](../)
* النطاق [System::Drawing::Drawing2D](../../)
* مكتبة [Aspose.Slides](../../../)
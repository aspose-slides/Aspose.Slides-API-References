---
title: InsertRowBefore()
second_title: مرجع API Aspose.Slides للغة C++
description: أدخل صفًا جديدًا قبل الصف المحدد. في البداية تكون جميع العناصر في الصف الجديد قيمتها null.
type: docs
weight: 287
url: /ar/aspose.slides.mathtext/mathmatrix/insertrowbefore/
---
## MathMatrix::InsertRowBefore(int32_t) طريقة

أدخل صفًا جديدًا قبل الصف المحدد. في البداية جميع العناصر في الصف الجديد هي null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowBefore(int32_t rowIndex) override
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| rowIndex | **int32_t** | فهرس الصف الذي سيُضاف قبله الصف الجديد |

## ملاحظات



مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowBefore(1);
```

## راجع أيضًا

* الفئة [MathMatrix](../)
* النطاق [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)
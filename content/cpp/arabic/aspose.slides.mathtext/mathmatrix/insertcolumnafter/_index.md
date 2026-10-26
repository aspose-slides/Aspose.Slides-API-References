---
title: InsertColumnAfter()
second_title: Aspose.Slides لـ C++ مرجع API
description: إدراج عمود جديد بعد العمود المحدد. في البداية تكون جميع العناصر في العمود الجديد فارغة.
type: docs
weight: 339
url: /ar/aspose.slides.mathtext/mathmatrix/insertcolumnafter/
---
## MathMatrix::InsertColumnAfter(int32_t) طريقة

أدخل عمودًا جديدًا بعد العمود المحدد. في البداية تكون جميع العناصر في العمود الجديد فارغة.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnAfter(int32_t columnIndex) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| columnIndex | **int32_t** | فهرس العمود الذي يليه يتم إدخال عمود جديد |

## ملاحظات

مثال:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnAfter(0);
```

## أنظر أيضًا

* فئة [MathMatrix](../)
* مساحة الأسماء [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)
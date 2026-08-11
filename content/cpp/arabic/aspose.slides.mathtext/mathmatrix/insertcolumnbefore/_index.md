---
title: InsertColumnBefore()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: إدراج عمود جديد قبل العمود المحدد. في البداية تكون جميع العناصر في العمود الجديد فارغة.
type: docs
weight: 326
url: /ar/aspose.slides.mathtext/mathmatrix/insertcolumnbefore/
---
## MathMatrix::InsertColumnBefore(int32_t) طريقة

إدراج عمود جديد قبل العمود المحدد. في البداية تكون جميع العناصر في العمود الجديد فارغة.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnBefore(int32_t columnIndex) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| columnIndex | **int32_t** | مؤشر العمود الذي يسبقه إدراج عمود جديد |
## ملاحظات



مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## انظر أيضاً

* الفئة [MathMatrix](../)
* النطاق [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)
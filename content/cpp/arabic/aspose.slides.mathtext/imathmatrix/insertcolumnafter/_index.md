---
title: InsertColumnAfter()
second_title: مرجع API Aspose.Slides للغة C++
description: إدراج عمود جديد بعد العمود المحدد. في البداية تكون جميع العناصر في العمود الجديد قيمتها null.
type: docs
weight: 326
url: /ar/aspose.slides.mathtext/imathmatrix/insertcolumnafter/
---
## IMathMatrix::InsertColumnAfter(int32_t) طريقة

إدراج عمود جديد بعد العمود المحدد. في البداية تكون جميع العناصر في العمود الجديد قيمتها null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnAfter(int32_t columnIndex)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| columnIndex | **int32_t** | الفهرس للعمود الذي يلي إدراجه عمود جديد |
## ملاحظات



مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnAfter(0);
```

## انظر أيضًا

* الفئة [IMathMatrix](../)
* النطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)
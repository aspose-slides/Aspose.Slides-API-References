---
title: InsertColumnBefore()
second_title: Aspose.Slides لـ C++ مرجع API
description: إدراج عمود جديد قبل العمود المحدد. في البداية تكون جميع العناصر في العمود الجديد فارغة.
type: docs
weight: 313
url: /ar/aspose.slides.mathtext/imathmatrix/insertcolumnbefore/
---
## IMathMatrix::InsertColumnBefore(int32_t) طريقة

إدراج عمود جديد قبل العمود المحدد. في البداية تكون جميع العناصر في العمود الجديد فارغة.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnBefore(int32_t columnIndex)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| columnIndex | **int32_t** | فهرس العمود الذي سيُضاف قبلّه عمود جديد |
## ملاحظات



مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## انظر أيضًا

* فئة [IMathMatrix](../)
* مساحة الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)
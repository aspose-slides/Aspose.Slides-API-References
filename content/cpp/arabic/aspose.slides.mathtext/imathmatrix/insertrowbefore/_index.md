---
title: InsertRowBefore()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: إدراج صف جديد قبل الصف المحدد. في البداية تكون جميع العناصر في الصف الجديد قيمتها null.
type: docs
weight: 274
url: /ar/aspose.slides.mathtext/imathmatrix/insertrowbefore/
---
## IMathMatrix::InsertRowBefore(int32_t) طريقة

إدراج صف جديد قبل الصف المحدد. في البداية تكون جميع العناصر في الصف الجديد قيمتها null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowBefore(int32_t rowIndex)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rowIndex | **int32_t** | فهرس الصف الذي يسبق إدراج صف جديد |
## ملاحظات

مثال:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowBefore(1);
```

## انظر أيضًا

* فئة [IMathMatrix](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)
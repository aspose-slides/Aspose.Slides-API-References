---
title: InsertRowAfter()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: إدراج صف جديد بعد الصف المحدد. في البداية تكون جميع العناصر في الصف الجديد null.
type: docs
weight: 300
url: /ar/aspose.slides.mathtext/mathmatrix/insertrowafter/
---
## طريقة MathMatrix::InsertRowAfter(int32_t)

إدراج صف جديد بعد الصف المحدد. في البداية تكون جميع العناصر في الصف الجديد null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowAfter(int32_t rowIndex) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rowIndex | **int32_t** | فهرس الصف الذي يليه يتم إدراج صف جديد |

## ملاحظات



مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## انظر أيضًا

* الفئة [MathMatrix](../)
* مساحة الاسم [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)
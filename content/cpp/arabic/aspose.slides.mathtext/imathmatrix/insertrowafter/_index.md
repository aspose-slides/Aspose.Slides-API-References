---
title: InsertRowAfter()
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للـ C++
description: أدخل صفًا جديدًا بعد الصف المحدد. في البداية جميع العناصر في الصف الجديد هي null.
type: docs
weight: 287
url: /ar/aspose.slides.mathtext/imathmatrix/insertrowafter/
---
## IMathMatrix::InsertRowAfter(int32_t) طريقة

أدخل صفًا جديدًا بعد الصف المحدد. في البداية جميع العناصر في الصف الجديد هي null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowAfter(int32_t rowIndex)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rowIndex | **int32_t** | فهرس الصف الذي يُتبع بإدراج صف جديد |
## ملاحظات

مثال:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## انظر أيضًا

* فئة [IMathMatrix](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)
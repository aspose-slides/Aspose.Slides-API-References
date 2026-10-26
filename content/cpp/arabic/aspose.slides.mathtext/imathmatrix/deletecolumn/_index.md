---
title: DeleteColumn()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: يحذف العمود المحدد
type: docs
weight: 339
url: /ar/aspose.slides.mathtext/imathmatrix/deletecolumn/
---
## IMathMatrix::DeleteColumn(int32_t) طريقة

يحذف العمود المحدد

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::DeleteColumn(int32_t columnIndex)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| columnIndex | **int32_t** | الفهرس الصفري للعمود المراد حذفه. |
## ملاحظات



مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteColumn(0);
```

## انظر أيضًا

* الفئة [IMathMatrix](../)
* النطاق [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)
---
title: DeleteColumn()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحذف العمود المحدد
type: docs
weight: 352
url: /ar/aspose.slides.mathtext/mathmatrix/deletecolumn/
---
## MathMatrix::DeleteColumn(int32_t) طريقة

يحذف العمود المحدد

```cpp
void Aspose::Slides::MathText::MathMatrix::DeleteColumn(int32_t columnIndex) override
```

### المعطيات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| columnIndex | **int32_t** | الفهرس الصفري للعمود المراد حذفه. |
## ملاحظات



مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteColumn(0);
```

## أنظر أيضًا

* الفئة [MathMatrix](../)
* النطاق [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)
---
title: get_MinColumnWidth()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "الحد الأدنى لعرض العمود بوحدة twips (1/20 من النقطة) يتم إضافة مسافة الفجوة (المعروفة أيضًا باسم \\u201CColumn Gap\\u201D أو \\u201CGap Width\\u201D) إلى MinColumnWidth لتحديد إجمالي تباعد أعمدة المصفوفة (المسافة بين الحواف المتساوية للأعمدة المختلفة). الافتراضي: 0."
type: docs
weight: 79
url: /ar/aspose.slides.mathtext/imathmatrix/get_mincolumnwidth/
---
## IMathMatrix::get_MinColumnWidth() طريقة

الحد الأدنى لعرض العمود بوحدة twips (1/20 من النقطة). يتم إضافة مسافة الفجوة (المعروفة أيضًا باسم “Column Gap” أو “Gap Width”) إلى MinColumnWidth لتحديد إجمالي Matrix [Column](../../../aspose.slides/column/) المسافة (المسافة بين الحواف المتساوية لأعمدة مختلفة). الافتراضي: 0.

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_MinColumnWidth()=0
```

## ملاحظات

مثال:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_MinColumnWidth(20);
```

## انظر أيضًا

* الفئة [IMathMatrix](../)
* النطاق [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)
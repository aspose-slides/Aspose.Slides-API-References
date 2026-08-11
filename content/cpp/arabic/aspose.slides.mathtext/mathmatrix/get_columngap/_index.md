---
title: get_ColumnGap()
second_title: Aspose.Slides مرجع API لـ C++
description: "قيمة الفاصل الأفقي بين أعمدة المصفوفة؛ إذا تم تعيين ColumnGapRule إلى 3 (\"Exactly\"), فسيتم تفسير الوحدة كـ twips (1/20 من النقطة) إذا تم تعيين ColumnGapRule إلى 4 (\"Multiple\"), فسيتم تفسير الوحدة كعدد من الزيادات 0.5 em. في الحالات الأخرى يتم تجاهلها. الافتراضي: 0"
type: docs
weight: 131
url: /ar/aspose.slides.mathtext/mathmatrix/get_columngap/
---
## MathMatrix::get_ColumnGap() طريقة

القيمة الأفقية للمسافة بين أعمدة المصفوفة؛ إذا تم ضبط ColumnGapRule على 3 ("Exactly")، يُفسَّر الوحد كـ twips (1/20 من النقطة). إذا تم ضبط ColumnGapRule على 4 ("Multiple")، يُفسَّر الوحد كعدد من الزيادات 0.5 em. في حالات أخرى يتم تجاهله. الافتراضي: 0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_ColumnGap() override
```

## ملاحظات

مثال:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## انظر أيضًا

* الفئة [MathMatrix](../)
* النطاق [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)
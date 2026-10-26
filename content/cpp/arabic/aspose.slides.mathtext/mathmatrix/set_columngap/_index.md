---
title: set_ColumnGap()
second_title: Aspose.Slides لـ C++ مرجع API
description: "قيمة التباعد الأفقي بين أعمدة مصفوفة؛ إذا تم ضبط ColumnGapRule على 3 (\"Exactly\"), فستُفسر الوحدة كـ twips (1/20 من النقطة) إذا تم ضبط ColumnGapRule على 4 (\"Multiple\"), فستُفسر الوحدة كعدد من الزيادات 0.5 em. في الحالات الأخرى يتم التجاهل. الافتراضي: 0"
type: docs
weight: 144
url: /ar/aspose.slides.mathtext/mathmatrix/set_columngap/
---
## MathMatrix::set_ColumnGap(uint32_t) طريقة

قيمة التباعد الأفقي بين أعمدة المصفوفة؛ إذا تم ضبط ColumnGapRule على 3 ("Exactly"), فسيتم تفسير الوحدة كـ twips (1/20 من النقطة) إذا تم ضبط ColumnGapRule على 4 ("Multiple"), فسيتم تفسير الوحدة كعدد من الزيادات 0.5 em. في الحالات الأخرى يتم تجاهلها. الافتراضي: 0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_ColumnGap(uint32_t value) override
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
* مساحة الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)
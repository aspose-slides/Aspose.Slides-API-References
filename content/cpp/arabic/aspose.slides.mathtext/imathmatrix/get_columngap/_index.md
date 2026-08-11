---
title: get_ColumnGap()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "قيمة المسافة الأفقية بين أعمدة المصفوفة؛ إذا تم تعيين ColumnGapRule إلى 3 (\"Exactly\"), فإن الوحدة تُفسَّر كـ twips (1/20 من النقطة) إذا تم تعيين ColumnGapRule إلى 4 (\"Multiple\"), فإن الوحدة تُفسَّر كعدد من الزيادات 0.5 em. في الحالات الأخرى يتم تجاهلها. الافتراضي: 0"
type: docs
weight: 131
url: /ar/aspose.slides.mathtext/imathmatrix/get_columngap/
---
## IMathMatrix::get_ColumnGap() طريقة

قيمة المسافة الأفقية بين أعمدة المصفوفة؛ إذا تم ضبط ColumnGapRule على 3 ("Exactly"), فإن الوحدة تُفسَّر كـ twips (1/20 من النقطة) إذا تم ضبط ColumnGapRule على 4 ("Multiple"), فإن الوحدة تُفسَّر كعدد من الزيادة 0.5 em. في الحالات الأخرى يتم تجاهلها. الافتراضي: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_ColumnGap()=0
```

## ملاحظات

مثال:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## انظر أيضًا

* الفئة [IMathMatrix](../)
* مساحة الاسم [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)
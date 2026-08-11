---
title: set_ColumnGap()
second_title: مرجع API Aspose.Slides للـ C++
description: "قيمة الفاصل الأفقي بين أعمدة المصفوفة؛ إذا تم ضبط ColumnGapRule إلى 3 (\"Exactly\"), فإن الوحدة تُفسَّر كـ twips (1/20 من النقطة) إذا تم ضبط ColumnGapRule إلى 4 (\"Multiple\"), فإن الوحدة تُفسَّر كعدد من الزيادات بمقدار 0.5 em. في الحالات الأخرى يتم تجاهلها. الافتراضي: 0"
type: docs
weight: 144
url: /ar/aspose.slides.mathtext/imathmatrix/set_columngap/
---
## IMathMatrix::set_ColumnGap(uint32_t) method


قيمة الفاصل الأفقي بين أعمدة المصفوفة؛ إذا تم ضبط ColumnGapRule إلى 3 ("Exactly")، فإن الوحدة تُفسَّر كـ twips (1/20 من النقطة) إذا تم ضبط ColumnGapRule إلى 4 ("Multiple")، فإن الوحدة تُفسَّر كعدد من الزيادات بمقدار 0.5 em. في الحالات الأخرى يتم تجاهلها. الافتراضي: 0

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_ColumnGap(uint32_t value)=0
```

## ملاحظات


مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## انظر أيضًا

* الصنف [IMathMatrix](../)
* النطاق [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)
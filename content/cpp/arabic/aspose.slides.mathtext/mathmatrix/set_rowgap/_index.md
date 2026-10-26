---
title: set_RowGap()
second_title: Aspose.Slides لـ C++ مرجع API
description: "قيمة التباعد العمودي بين صفوف المصفوفة; إذا تم تعيين RowGapRule إلى 3 (\"Exactly\"), فإن الوحدة تُفسَّر كـ twips (1/20 من النقطة) إذا تم تعيين RowGapRule إلى 4 (\"Multiple\"), فإن الوحدة تُفسَّر كخطوط نصفية. الافتراضي: 0"
type: docs
weight: 196
url: /ar/aspose.slides.mathtext/mathmatrix/set_rowgap/
---
## MathMatrix::set_RowGap(uint32_t) طريقة

قيمة التباعد العمودي بين صفوف المصفوفة؛ إذا تم تعيين RowGapRule إلى 3 ("Exactly")، فإن الوحدة تُفسَّر كـ twips (1/20 من النقطة) إذا تم تعيين RowGapRule إلى 4 ("Multiple")، فإن الوحدة تُفسَّر كخطوط نصفية. الافتراضي: 0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_RowGap(uint32_t value) override
```

## ملاحظات


مثال:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## انظر أيضاً

* فئة [MathMatrix](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)
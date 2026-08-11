---
title: get_RowGap()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: "قيمة التباعد العمودي بين صفوف المصفوفة; إذا تم تعيين RowGapRule إلى 3 (\"Exactly\"), تُفسر الوحدة كـ twips (1/20 من النقطة) إذا تم تعيين RowGapRule إلى 4 (\"Multiple\"), تُفسر الوحدة كنصف أسطر. الافتراضي: 0"
type: docs
weight: 183
url: /ar/aspose.slides.mathtext/mathmatrix/get_rowgap/
---
## MathMatrix::get_RowGap() طريقة

قيمة التباعد العمودي بين صفوف المصفوفة؛ إذا تم تعيين RowGapRule إلى 3 ("Exactly"), فتُفسر الوحدة كـ twips (1/20th من نقطة) إذا تم تعيين RowGapRule إلى 4 ("Multiple"), فتُفسر الوحدة كنصف أسطر. الافتراضي: 0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_RowGap() override
```

## ملاحظات

مثال:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## انظر أيضًا

* الفئة [MathMatrix](../)
* مساحة الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)
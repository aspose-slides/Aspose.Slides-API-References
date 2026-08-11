---
title: set_RowGap()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "قيمة التباعد العمودي بين صفوف المصفوفة؛ إذا تم تعيين RowGapRule إلى 3 (\"Exactly\"), فسيتم تفسير الوحدة كـ twips (1/20 من النقطة) إذا تم تعيين RowGapRule إلى 4 (\"Multiple\"), فسيتم تفسير الوحدة كخطوط نصفية. الافتراضي: 0"
type: docs
weight: 196
url: /ar/aspose.slides.mathtext/imathmatrix/set_rowgap/
---
## IMMathMatrix::set_RowGap(uint32_t) طريقة


قيمة التباعد العمودي بين صفوف المصفوفة؛ إذا تم تعيين RowGapRule إلى 3 ("Exactly") فسيتم تفسير الوحدة كـ twips (1/20 من النقطة) إذا تم تعيين RowGapRule إلى 4 ("Multiple") فسيتم تفسير الوحدة كخطوط نصفية. الافتراضي: 0

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_RowGap(uint32_t value)=0
```

## ملاحظات


مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## انظر أيضًا

* الفئة [IMathMatrix](../)
* المجال [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)
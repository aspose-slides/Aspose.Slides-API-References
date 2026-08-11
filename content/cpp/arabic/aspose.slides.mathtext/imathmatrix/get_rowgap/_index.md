---
title: get_RowGap()
second_title: مرجع API Aspose.Slides للغة C++
description: "قيمة الفاصل الرأسي بين صفوف مصفوفة؛ إذا تم تعيين RowGapRule إلى 3 (\"Exactly\")، يتم تفسير الوحدة كـ twips (1/20 من النقطة) إذا تم تعيين RowGapRule إلى 4 (\"Multiple\")، يتم تفسير الوحدة كخطوط نصفية. القيمة الافتراضية: 0"
type: docs
weight: 183
url: /ar/aspose.slides.mathtext/imathmatrix/get_rowgap/
---
## IMathMatrix::get_RowGap() الطريقة

قيمة الفاصل الرأسي بين صفوف المصفوفة؛ إذا تم تعيين RowGapRule إلى 3 ("Exactly")، فإن الوحدة تُفسَّر كـ twips (1/20 من النقطة) إذا تم تعيين RowGapRule إلى 4 ("Multiple")، فإن الوحدة تُفسَّر كـ نصف-خطوط. القيمة الافتراضية: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_RowGap()=0
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
* النطاق [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)
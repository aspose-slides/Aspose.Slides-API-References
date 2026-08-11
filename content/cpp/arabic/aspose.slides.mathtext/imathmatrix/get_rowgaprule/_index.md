---
title: get_RowGapRule()
second_title: مرجع API Aspose.Slides للـ C++
description: "نوع المسافة الرأسية بين صفوف المصفوفة؛ يمكن أن تكون وحدات المسافة الرأسية سطراً أو نقطة (محفوظة كـ twips). الافتراضي: SingleSpacingGap (0)"
type: docs
weight: 157
url: /ar/aspose.slides.mathtext/imathmatrix/get_rowgaprule/
---
## IMathMatrix::get_RowGapRule() طريقة

نوع المسافة الرأسية بين صفوف المصفوفة؛ يمكن أن تكون وحدات المسافة الرأسية سطراً أو نقطة (محفوظة كـ twips). الافتراضي: SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_RowGapRule()=0
```

## ملاحظات

مثال:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## انظر أيضًا

* تعداد [MathSpacingRules](../../mathspacingrules/)
* فئة [IMathMatrix](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)
---
title: get_RowGapRule()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "نوع التباعد الرأسي بين صفوف المصفوفة؛ يمكن أن تكون وحدات التباعد الرأسي خطوطًا أو نقاطًا (مخزنة كوحدات twips). الافتراضي: SingleSpacingGap (0)"
type: docs
weight: 157
url: /ar/aspose.slides.mathtext/mathmatrix/get_rowgaprule/
---
## MathMatrix::get_RowGapRule() طريقة

نوع التباعد الرأسي بين صفوف المصفوفة؛ يمكن أن تكون وحدات التباعد الرأسي خطوطًا أو نقاطًا (مخزنة كوحدات twips). الافتراضي: SingleSpacingGap (0)

```cpp
MathSpacingRules Aspose::Slides::MathText::MathMatrix::get_RowGapRule() override
```

## ملاحظات

مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## انظر أيضًا

* Enum [MathSpacingRules](../../mathspacingrules/)
* فئة [MathMatrix](../)
* نطاق [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
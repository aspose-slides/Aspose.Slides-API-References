---
title: set_RowGapRule()
second_title: Aspose.Slides للغة C++ مرجع API
description: "نوع الفاصل العمودي بين صفوف المصفوفة؛ يمكن أن تكون وحدات الفاصل العمودي أسطرًا أو نقاطًا (مخزنة كوحدات twips). الافتراضي: SingleSpacingGap (0)"
type: docs
weight: 170
url: /ar/aspose.slides.mathtext/mathmatrix/set_rowgaprule/
---
## MathMatrix::set_RowGapRule(MathSpacingRules) طريقة


نوع الفاصل الرأسي بين صفوف المصفوفة؛ وحدات الفاصل الرأسي يمكن أن تكون أسطر أو نقاط (مخزنة كوحدات twips). الافتراضي: SingleSpacingGap (0)

```cpp
void Aspose::Slides::MathText::MathMatrix::set_RowGapRule(MathSpacingRules value) override
```

## ملاحظات


مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## انظر أيضًا

* تعداد [MathSpacingRules](../../mathspacingrules/)
* فئة [MathMatrix](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)
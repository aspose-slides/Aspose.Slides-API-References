---
title: set_RowGapRule()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "نوع الفجوة العمودية بين صفوف المصفوفة؛ يمكن أن تكون وحدات الفجوة العمودية أسطرًا أو نقاطًا (مخزنة كـ twips). الافتراضي: SingleSpacingGap (0)"
type: docs
weight: 170
url: /ar/aspose.slides.mathtext/imathmatrix/set_rowgaprule/
---
## IMathMatrix::set_RowGapRule(MathSpacingRules) طريقة

نوع الفجوة العمودية بين صفوف المصفوفة؛ يمكن أن تكون وحدات الفجوة العمودية أسطرًا أو نقاطًا (مخزنة كـ twips). الافتراضي: SingleSpacingGap (0)

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_RowGapRule(MathSpacingRules value)=0
```

## ملاحظات

مثال:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## أنظر أيضاً

* Enum [MathSpacingRules](../../mathspacingrules/)
* فئة [IMathMatrix](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)
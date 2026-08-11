---
title: get_ColumnGapRule()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "نوع التباعد الأفقي بين أعمدة المصفوفة؛ يمكن أن تكون وحدات التباعد الأفقي إيم أو نقاط (مخزنة كوحدات twips). الافتراضي: SingleSpacingGap (0)"
type: docs
weight: 105
url: /ar/aspose.slides.mathtext/mathmatrix/get_columngaprule/
---
## MathMatrix::get_ColumnGapRule() طريقة

نوع التباعد الأفقي بين أعمدة المصفوفة؛ يمكن أن تكون وحدات التباعد الأفقي إيم أو نقاط (مخزنة كوحدات twips). الافتراضي: SingleSpacingGap (0)

```cpp
MathSpacingRules Aspose::Slides::MathText::MathMatrix::get_ColumnGapRule() override
```

## ملاحظات

مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## انظر أيضًا

* تعداد [MathSpacingRules](../../mathspacingrules/)
* فئة [MathMatrix](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)
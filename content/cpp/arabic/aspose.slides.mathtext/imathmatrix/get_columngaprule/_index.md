---
title: get_ColumnGapRule()
second_title: Aspose.Slides للـ C++ – مرجع API
description: "نوع المسافات الأفقية بين أعمدة المصفوفة؛ يمكن أن تكون وحدات المسافة الأفقية إيم أو نقاط (مخزنة كوحدات twips). الافتراضي: SingleSpacingGap (0)"
type: docs
weight: 105
url: /ar/aspose.slides.mathtext/imathmatrix/get_columngaprule/
---
## IMathMatrix::get_ColumnGapRule() طريقة

نوع المسافات الأفقية بين أعمدة المصفوفة؛ يمكن أن تكون وحدات المسافة الأفقية إيم أو نقاط (مخزنة كوحدات twips). الافتراضي: SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_ColumnGapRule()=0
```

## ملاحظات

مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## انظر أيضًا

* تعداد [MathSpacingRules](../../mathspacingrules/)
* فئة [IMathMatrix](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)
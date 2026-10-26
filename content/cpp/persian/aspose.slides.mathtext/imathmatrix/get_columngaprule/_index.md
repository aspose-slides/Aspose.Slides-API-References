---
title: get_ColumnGapRule()
second_title: مرجع API Aspose.Slides برای C++
description: "نوع فاصله افقی بین ستون‌های یک ماتریس؛ واحدهای فاصله افقی می‌توانند ems یا points باشند (به صورت twips ذخیره می‌شوند). پیش‌فرض: SingleSpacingGap (0)"
type: docs
weight: 105
url: /fa/aspose.slides.mathtext/imathmatrix/get_columngaprule/
---
## IMathMatrix::get_ColumnGapRule() متد

نوع فاصله افقی بین ستون‌های یک ماتریس؛ واحدهای فاصله افقی می‌توانند em یا point باشند (به‌صورت twips ذخیره می‌شوند). مقدار پیش‌فرض: SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_ColumnGapRule()=0
```

## توضیحات

مثال:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## مراجع

* Enum [MathSpacingRules](../../mathspacingrules/)
* Class [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
---
title: get_ColumnGapRule()
second_title: مرجع API Aspose.Slides برای C++
description: "نوع فاصله افقی بین ستون‌های یک ماتریس؛ واحدهای فاصله افقی می‌توانند ems یا points باشند (به صورت twips ذخیره می‌شوند). پیش‌فرض: SingleSpacingGap (0)"
type: docs
weight: 105
url: /fa/aspose.slides.mathtext/mathmatrix/get_columngaprule/
---
## MathMatrix::get_ColumnGapRule() متد

نوع فاصله افقی بین ستون‌های یک ماتریس؛ واحدهای فاصله افقی می‌توانند ems یا points باشند (به صورت twips ذخیره می‌شوند). پیش‌فرض: SingleSpacingGap (0)

```cpp
MathSpacingRules Aspose::Slides::MathText::MathMatrix::get_ColumnGapRule() override
```

## توضیحات

مثال:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## موارد مرتبط

* Enum [MathSpacingRules](../../mathspacingrules/)
* کلاس [MathMatrix](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
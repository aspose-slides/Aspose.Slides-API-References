---
title: set_RowGapRule()
second_title: مرجع API Aspose.Slides برای C++
description: "نوع فاصله عمودی بین سطرهای یک ماتریس؛ واحدهای فاصله عمودی می‌توانند خط یا نقطه باشند (به صورت twips ذخیره می‌شوند). پیش‌فرض: SingleSpacingGap (0)"
type: docs
weight: 170
url: /fa/aspose.slides.mathtext/mathmatrix/set_rowgaprule/
---
## MathMatrix::set_RowGapRule(MathSpacingRules) متد

نوع فاصله عمودی بین سطرهای یک ماتریس؛ واحدهای فاصله عمودی می‌توانند خط یا نقطه باشند (به صورت twips ذخیره می‌شوند). پیش‌فرض: SingleSpacingGap (0)

```cpp
void Aspose::Slides::MathText::MathMatrix::set_RowGapRule(MathSpacingRules value) override
```
## توضیحات

مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```
## موارد مرتبط

* Enum [MathSpacingRules](../../mathspacingrules/)
* کلاس [MathMatrix](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
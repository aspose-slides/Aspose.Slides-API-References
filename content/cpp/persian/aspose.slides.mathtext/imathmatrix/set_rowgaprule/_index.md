---
title: set_RowGapRule()
second_title: Aspose.Slides برای C++ مرجع API
description: "نوع فاصله عمودی بین ردیف‌های یک ماتریس؛ واحدهای فاصله عمودی می‌توانند خطوط یا نقاط (به صورت twips ذخیره شده) باشند. پیش‌فرض: SingleSpacingGap (0)"
type: docs
weight: 170
url: /fa/aspose.slides.mathtext/imathmatrix/set_rowgaprule/
---
## IMathMatrix::set_RowGapRule(MathSpacingRules) متد

نوع فاصله عمودی بین ردیف‌های یک ماتریس؛ واحدهای فاصله عمودی می‌توانند خطوط یا نقاط (به صورت twips ذخیره شده) باشند. پیش‌فرض: SingleSpacingGap (0)

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_RowGapRule(MathSpacingRules value)=0
```

## توضیحات

مثال:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## موارد مرتبط

* Enum [MathSpacingRules](../../mathspacingrules/)
* کلاس [IMathMatrix](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
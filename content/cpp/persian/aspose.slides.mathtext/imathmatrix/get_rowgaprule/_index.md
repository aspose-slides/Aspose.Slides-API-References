---
title: get_RowGapRule()
second_title: Aspose.Slides برای C++ مرجع API
description: "نوع فاصله عمودی بین ردیف‌های یک ماتریس؛ واحدهای فاصله عمودی می‌توانند خطوط یا نقاط (به صورت تویپ ذخیره شده) باشند. پیش‌فرض: SingleSpacingGap (0)"
type: docs
weight: 157
url: /fa/aspose.slides.mathtext/imathmatrix/get_rowgaprule/
---
## IMathMatrix::get_RowGapRule() متد


نوع فاصله عمودی بین ردیف‌های یک ماتریس؛ واحدهای فاصله عمودی می‌تواند خطوط یا نقاط (به‌صورت تویپ ذخیره شده) باشد. پیش‌فرض: SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_RowGapRule()=0
```

## توضیحات


مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## همچنین ببینید

* enum [MathSpacingRules](../../mathspacingrules/)
* کلاس [IMathMatrix](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
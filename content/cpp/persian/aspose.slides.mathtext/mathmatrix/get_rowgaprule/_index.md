---
title: get_RowGapRule()
second_title: Aspose.Slides برای C++ مرجع API
description: "نوع فاصله عمودی بین سطرهای یک ماتریس؛ واحدهای فاصله عمودی می‌توانند به صورت خطوط یا نقاط (به‌صورت تویپ ذخیره شوند). پیش‌فرض: SingleSpacingGap (0)"
type: docs
weight: 157
url: /fa/aspose.slides.mathtext/mathmatrix/get_rowgaprule/
---
## MathMatrix::get_RowGapRule() متد

نوع فاصله عمودی بین سطرهای یک ماتریس؛ واحدهای فاصله عمودی می‌توانند به صورت خطوط یا نقاط (به‌صورت تویپ ذخیره شده) باشند. پیش‌فرض: SingleSpacingGap (0)

```cpp
MathSpacingRules Aspose::Slides::MathText::MathMatrix::get_RowGapRule() override
```

## ملاحظات


مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## موارد مرتبط

* شمارش [MathSpacingRules](../../mathspacingrules/)
* کلاس [MathMatrix](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
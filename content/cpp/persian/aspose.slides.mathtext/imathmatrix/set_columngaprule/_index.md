---
title: set_ColumnGapRule()
second_title: مرجع API Aspose.Slides برای C++
description: "نوع فضای افقی بین ستون‌های یک ماتریس; واحدهای فضای افقی می‌توانند ems یا points باشند (به‌صورت twips ذخیره می‌شوند). پیش‌فرض: SingleSpacingGap (0)"
type: docs
weight: 118
url: /fa/aspose.slides.mathtext/imathmatrix/set_columngaprule/
---
## IMMathMatrix::set_ColumnGapRule(MathSpacingRules) متد


نوع فضای افقی بین ستون‌های یک ماتریس؛ واحدهای فضای افقی می‌توانند ems یا points باشند (به‌صورت twips ذخیره می‌شوند). پیش‌فرض: SingleSpacingGap (0)

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_ColumnGapRule(MathSpacingRules value)=0
```

## توضیحات


مثال:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## موارد مرتبط

* شمارش [MathSpacingRules](../../mathspacingrules/)
* کلاس [IMathMatrix](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
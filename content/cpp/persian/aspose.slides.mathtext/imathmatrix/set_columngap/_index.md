---
title: set_ColumnGap()
second_title: Aspose.Slides برای C++ مرجع API
description: "مقدار فاصله افقی بین ستون‌های یک ماتریس؛ اگر ColumnGapRule برابر 3 (\"Exactly\") باشد، واحد به عنوان twips (1/20th of a point) تفسیر می‌شود. اگر ColumnGapRule برابر 4 (\"Multiple\") باشد، واحد به عنوان تعداد گام‌های 0.5 em تفسیر می‌شود. در سایر موارد نادیده گرفته می‌شود. پیش‌فرض: 0"
type: docs
weight: 144
url: /fa/aspose.slides.mathtext/imathmatrix/set_columngap/
---
## IMathMatrix::set_ColumnGap(uint32_t) متد

فاصله افقی بین ستون‌های یک ماتریس؛ اگر ColumnGapRule برابر 3 ("Exactly") باشد، واحد به صورت twips (1/20 نقطه) تفسیر می‌شود. اگر ColumnGapRule برابر 4 ("Multiple") باشد، واحد به صورت تعداد گام‌های 0.5 em تفسیر می‌شود. در سایر موارد نادیده گرفته می‌شود. پیش‌فرض: 0

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_ColumnGap(uint32_t value)=0
```

## توضیحات

مثال:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## مراجع مرتبط

* کلاس [IMathMatrix](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
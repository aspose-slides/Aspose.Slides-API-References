---
title: get_ColumnGap()
second_title: مرجع API Aspose.Slides برای C++
description: "مقدار فاصله افقی بین ستون‌های یک ماتریس؛ اگر ColumnGapRule برابر 3 (\"Exactly\") باشد، واحد به صورت twips (1/20 امتیاز) تفسیر می‌شود. اگر ColumnGapRule برابر 4 (\"Multiple\") باشد، واحد به عنوان تعداد افزایش‌های 0.5 em در نظر گرفته می‌شود. در موارد دیگر نادیده گرفته می‌شود. پیش‌فرض: 0"
type: docs
weight: 131
url: /fa/aspose.slides.mathtext/mathmatrix/get_columngap/
---
## MathMatrix::get_ColumnGap() متد


مقدار فاصله افقی بین ستون‌های یک ماتریس؛ اگر ColumnGapRule برابر 3 (\"Exactly\") باشد، واحد به عنوان twips (1/20th of a point) تفسیر می‌شود. اگر ColumnGapRule برابر 4 (\"Multiple\") باشد، واحد به عنوان تعداد افزایش‌های 0.5 em در نظر گرفته می‌شود. در سایر موارد نادیده گرفته می‌شود. پیش‌فرض: 0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_ColumnGap() override
```

## توضیحات


مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## مراجع

* کلاس [MathMatrix](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
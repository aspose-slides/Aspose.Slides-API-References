---
title: get_ColumnGap()
second_title: Aspose.Slides برای C++ مرجع API
description: "مقدار فاصله افقی بین ستون‌های یک ماتریس؛ اگر ColumnGapRule برابر 3 (\"دقیقاً\"), سپس واحد به صورت twips (1/20 امتیاز) تفسیر می‌شود. اگر ColumnGapRule برابر 4 (\"چندگانه\"), سپس واحد به عنوان تعداد 0.5 em افزایشت‌ها تفسیر می‌شود. در موارد دیگر نادیده گرفته می‌شود. پیش‌فرض: 0"
type: docs
weight: 131
url: /fa/aspose.slides.mathtext/imathmatrix/get_columngap/
---
## IMathMatrix::get_ColumnGap() متد

مقدار فاصله افقی بین ستون‌های یک ماتریس؛ اگر ColumnGapRule برابر 3 (\"Exactly\") باشد، واحد به صورت twips (1/20 امتیاز) تفسیر می‌شود. اگر ColumnGapRule برابر 4 (\"Multiple\") باشد، واحد به عنوان تعداد افزایش‌های 0.5 em در نظر گرفته می‌شود. در موارد دیگر نادیده گرفته می‌شود. پیش‌فرض: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_ColumnGap()=0
```

## توضیحات

مثال:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## موارد مرتبط

* کلاس [IMathMatrix](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
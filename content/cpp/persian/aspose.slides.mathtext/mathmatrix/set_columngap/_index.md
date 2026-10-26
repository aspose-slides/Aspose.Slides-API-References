---
title: set_ColumnGap()
second_title: مرجع API Aspose.Slides برای C++
description: "مقدار فاصله افقی بین ستون‌های یک ماتریس؛ اگر ColumnGapRule برابر 3 (\"Exactly\") باشد، واحد به عنوان twips (1/20 نقطه) تفسیر می‌شود. اگر ColumnGapRule برابر 4 (\"Multiple\") باشد، واحد به عنوان تعداد افزایشی 0.5 em تفسیر می‌شود. در موارد دیگر نادیده گرفته می‌شود. پیش‌فرض: 0"
type: docs
weight: 144
url: /fa/aspose.slides.mathtext/mathmatrix/set_columngap/
---
## MathMatrix::set_ColumnGap(uint32_t) متد

مقدار فاصله افقی بین ستون‌های یک ماتریس؛ اگر ColumnGapRule برابر 3 ("Exactly") باشد، واحد به عنوان twips (۱/۲۰ نقطه) تفسیر می‌شود. اگر ColumnGapRule برابر 4 ("Multiple") باشد، واحد به عنوان تعداد افزایش‌های 0.5 em تفسیر می‌شود. در سایر موارد نادیده گرفته می‌شود. پیش‌فرض: 0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_ColumnGap(uint32_t value) override
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
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
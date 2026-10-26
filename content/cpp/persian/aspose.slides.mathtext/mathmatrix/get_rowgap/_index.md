---
title: get_RowGap()
second_title: Aspose.Slides برای C++ مرجع API
description: "مقدار فاصله عمودی بین ردیف‌های یک ماتریس؛ اگر RowGapRule برابر 3 (\"Exactly\") باشد، واحد به صورت twips (1/20 نقطه) تفسیر می‌شود. اگر RowGapRule برابر 4 (\"Multiple\") باشد، واحد به صورت نیم‌خط تفسیر می‌شود. پیش‌فرض: 0"
type: docs
weight: 183
url: /fa/aspose.slides.mathtext/mathmatrix/get_rowgap/
---
## MathMatrix::get_RowGap() متد

مقدار فاصله عمودی بین ردیف‌های یک ماتریس؛ اگر RowGapRule برابر 3 ("Exactly") باشد، واحد به صورت twips (1/20 نقطه) تفسیر می‌شود. اگر RowGapRule برابر 4 ("Multiple") باشد، واحد به صورت نیم‌خط تفسیر می‌شود. پیش‌فرض: 0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_RowGap() override
```

## ملاحظات

مثال:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## موارد مرتبط

* کلاس [MathMatrix](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
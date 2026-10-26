---
title: set_RowGap()
second_title: مرجع API Aspose.Slides برای C++
description: "مقدار فاصله عمودی بین سطرهای یک ماتریس؛ اگر RowGapRule بر روی 3 (\"Exactly\") تنظیم شود، واحد به صورت تویپ (1/20th of a point) تفسیر می‌شود. اگر RowGapRule بر روی 4 (\"Multiple\") تنظیم شود، واحد به صورت نیم‌خط تفسیر می‌شود. پیش‌فرض: 0"
type: docs
weight: 196
url: /fa/aspose.slides.mathtext/mathmatrix/set_rowgap/
---
## MathMatrix::set_RowGap(uint32_t) متد

مقدار فاصله عمودی بین سطرهای یک ماتریس؛ اگر RowGapRule بر روی 3 ("Exactly") تنظیم شود، واحد به صورت تویپ (1/20th of a point) تفسیر می‌شود. اگر RowGapRule بر روی 4 ("Multiple") تنظیم شود، واحد به صورت نیم‌خط تفسیر می‌شود. پیش‌فرض: 0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_RowGap(uint32_t value) override
```

## توضیحات

مثال:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## موارد مرتبط

* کلاس [MathMatrix](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
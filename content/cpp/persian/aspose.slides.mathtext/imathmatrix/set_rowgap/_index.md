---
title: set_RowGap()
second_title: "مرجع API Aspose.Slides برای C++"
description: "مقدار فاصله عمودی بین سطرهای یک ماتریس؛ اگر RowGapRule برابر ۳ (\"Exactly\") تنظیم شود، واحد به صورت تویپ (۱/۲۰ نقطه) تفسیر می‌شود. اگر RowGapRule برابر ۴ (\"Multiple\") تنظیم شود، واحد به صورت نیم‌خط تفسیر می‌شود. پیش‌فرض: ۰"
type: docs
weight: 196
url: /fa/aspose.slides.mathtext/imathmatrix/set_rowgap/
---
## IMathMatrix::set_RowGap(uint32_t) متد

مقدار فاصله عمودی بین سطرهای یک ماتریس؛ اگر RowGapRule برابر ۳ (\"Exactly\") تنظیم شده باشد، واحد به صورت تویپ (۱/۲۰ نقطه) تفسیر می‌شود. اگر RowGapRule برابر ۴ (\"Multiple\") تنظیم شده باشد، واحد به صورت نیم‌خط تفسیر می‌شود. پیش‌فرض: ۰

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_RowGap(uint32_t value)=0
```

## توضیحات

مثال:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## موارد مرتبط

* کلاس [IMathMatrix](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
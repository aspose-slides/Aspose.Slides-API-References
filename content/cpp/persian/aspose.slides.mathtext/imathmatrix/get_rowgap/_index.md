---
title: get_RowGap()
second_title: مرجع API Aspose.Slides برای C++
description: "مقدار فاصله عمودی بین ردیف‌های یک ماتریکس؛ اگر RowGapRule روی 3 (\"Exactly\") تنظیم شود، واحد به صورت twips (1/20th of a point) تفسیر می‌شود. اگر RowGapRule روی 4 (\"Multiple\") تنظیم شود، واحد به صورت نیم-خط تفسیر می‌شود. پیش‌فرض: 0"
type: docs
weight: 183
url: /fa/aspose.slides.mathtext/imathmatrix/get_rowgap/
---
## IMathMatrix::get_RowGap() متد


مقدار فاصله عمودی بین ردیف‌های یک ماتریکس؛ اگر RowGapRule روی 3 (\"Exactly\") تنظیم شود، واحد به صورت twips (1/20th of a point) تفسیر می‌شود. اگر RowGapRule روی 4 (\"Multiple\") تنظیم شود، واحد به صورت نیم-خط تفسیر می‌شود. پیش‌فرض: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_RowGap()=0
```

## توضیحات


مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## مراجع

* کلاس [IMathMatrix](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
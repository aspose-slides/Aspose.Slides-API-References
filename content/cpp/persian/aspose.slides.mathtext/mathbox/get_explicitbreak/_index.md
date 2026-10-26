---
title: get_ExplicitBreak()
second_title: مرجع API Aspose.Slides برای C++
description: "شکست صریح مشخص می‌کند که آیا در ابتدای شیء Box یک شکست خط وجود دارد یا خیر، به‌طوری که خط در ابتدای شیء جعبه بسته شود. تعداد عملگر در خط قبلی متن ریاضی را که باید به عنوان نقطه تراز برای خط کنونی متن ریاضی استفاده شود مشخص می‌کند. مقادیر ممکن: 1..255 پیش‌فرض: 0 (بدون شکست صریح)"
type: docs
weight: 118
url: /fa/aspose.slides.mathtext/mathbox/get_explicitbreak/
---
## MathBox::get_ExplicitBreak() متد


شکست صریح مشخص می‌کند که آیا در ابتدای شیء Box یک شکست خط وجود دارد یا خیر، به‌طوری‌که خط در ابتدای شیء Box بسته شود. تعداد عملگر در خط قبلی متن ریاضی را که باید به عنوان نقطه تراز برای خط کنونی متن ریاضی استفاده شود مشخص می‌کند مقادیر ممکن: 1..255 پیش‌فرض: 0 (بدون شکست صریح)

```cpp
uint8_t Aspose::Slides::MathText::MathBox::get_ExplicitBreak() override
```

## توضیحات


مثال: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## موارد مرتبط

* کلاس [MathBox](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
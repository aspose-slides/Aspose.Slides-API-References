---
title: set_ExplicitBreak()
second_title: مرجع API Aspose.Slides برای C++
description: "شکست صریح تعیین می‌کند آیا در ابتدای شیء Box یک شکست خط وجود دارد یا نه، به‌طوری که خط در ابتدای شیء box بسته شود. تعداد عملگر در خط قبلی متن ریاضی که به عنوان نقطه تراز برای خط جاری متن ریاضی استفاده می‌شود، مشخص می‌کند. مقادیر ممکن: 1..255 پیش‌فرض: 0 (بدون شکست صریح)"
type: docs
weight: 131
url: /fa/aspose.slides.mathtext/mathbox/set_explicitbreak/
---
## MathBox::set_ExplicitBreak(uint8_t) متد

شکست صریح مشخص می‌کند که آیا در ابتدای شیء Box یک شکست خط وجود دارد یا خیر، به‌طوری که خط در ابتدای شیء box بسته شود. تعداد عملگر در خط قبلی متن ریاضی که به عنوان نقطه تراز برای خط جاری متن ریاضی استفاده خواهد شد را مشخص می‌کند. مقادیر ممکن: 1..255 پیش‌فرض: 0 (بدون شکست صریح)

```cpp
void Aspose::Slides::MathText::MathBox::set_ExplicitBreak(uint8_t value) override
```

## توضیحات

مثال:
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## همچنین ببینید

* کلاس [MathBox](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
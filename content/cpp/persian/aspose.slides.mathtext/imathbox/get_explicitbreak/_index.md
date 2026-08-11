---
title: get_ExplicitBreak()
second_title: Aspose.Slides برای C++ مرجع API
description: "شکست صریح تعیین می‌کند که آیا در ابتدای شیء Box یک شکست خط وجود دارد یا خیر، به گونه‌ای که خط در ابتدای شیء جعبه پیچیده شود. عدد اپراتور در خط قبلی متن ریاضی که به عنوان نقطه تراز برای خط فعلی متن ریاضی استفاده می‌شود را مشخص می‌کند. مقادیر ممکن: 1..255 پیش‌فرض: 0 (بدون شکست صریح)"
type: docs
weight: 118
url: /fa/aspose.slides.mathtext/imathbox/get_explicitbreak/
---
## IMathBox::get_ExplicitBreak() متد

شکست صریح تعیین می‌کند که آیا در ابتدای شیء Box یک شکست خط وجود دارد یا خیر، به گونه‌ای که خط در ابتدای شیء جعبه پیچیده شود. عدد اپراتور در خط قبلی متن ریاضی که به عنوان نقطه تراز برای خط فعلی متن ریاضی استفاده می‌شود را مشخص می‌کند. مقادیر ممکن: 1..255 پیش‌فرض: 0 (بدون شکست صریح)

```cpp
virtual uint8_t Aspose::Slides::MathText::IMathBox::get_ExplicitBreak()=0
```

## توضیحات

مثال:
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## مراجع

* کلاس [IMathBox](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
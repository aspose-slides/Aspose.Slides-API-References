---
title: set_ExplicitBreak()
second_title: Aspose.Slides برای C++ مرجع API
description: "شکست صریح مشخص می‌کند آیا در ابتدای شیء Box یک شکست خط وجود دارد یا خیر، به طوری که خط در ابتدای شیء جعبه بسته شود. تعداد عملگر در خط قبلی متن ریاضی که به عنوان نقطه تراز برای خط جاری متن ریاضی استفاده می‌شود را مشخص می‌کند. مقادیر ممکن: 1..255 پیش‌فرض: 0 (بدون شکست صریح)"
type: docs
weight: 131
url: /fa/aspose.slides.mathtext/imathbox/set_explicitbreak/
---
## IMathBox::set_ExplicitBreak(uint8_t) متد

شکست صریح تعیین می‌کند آیا در ابتدای شیء جعبه یک شکست خط وجود دارد یا خیر، به‌طوری که خط در ابتدای شیء جعبه بسته شود. تعداد عملگر در خط قبلی متن ریاضی که به عنوان نقطه تراز برای خط جاری متن ریاضی استفاده می‌شود را مشخص می‌کند. مقادیر ممکن: 1..255 پیش‌فرض: 0 (بدون شکست صریح)

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_ExplicitBreak(uint8_t value)=0
```

## توضیحات

مثال:
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## موارد مرتبط

* کلاس [IMathBox](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
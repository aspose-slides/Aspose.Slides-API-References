---
title: set_OperatorEmulator()
second_title: Aspose.Slides برای C++ مرجع API
description: "شبیه‌ساز عملگر. وقتی مقدار true باشد، جعبه و محتویات آن همانند یک عملگر واحد رفتار می‌کنند و ویژگی‌های یک عملگر را به ارث می‌برند. این به این معنی است که، به عنوان مثال، کاراکتر می‌تواند به عنوان نقطه‌ای برای شکستن خط استفاده شود و می‌تواند نسبت به عملگرهای دیگر تراز شود. شبیه‌سازهای عملگر اغلب زمانی استفاده می‌شوند که یک یا چند گلیف برای تشکیل یک عملگر ترکیب می‌شوند، مانند '=='. مقدار پیش‌فرض: false"
type: docs
weight: 27
url: /fa/aspose.slides.mathtext/imathbox/set_operatoremulator/
---
## IMMathBox::set_OperatorEmulator(bool) method

شبیه‌ساز عملگر. وقتی مقدار true باشد، جعبه و محتویات آن همانند یک عملگر واحد رفتار می‌کنند و ویژگی‌های یک عملگر را به ارث می‌برند. این به این معنی است که، به عنوان مثال، کاراکتر می‌تواند به عنوان نقطه‌ای برای شکست خط استفاده شود و می‌تواند نسبت به عملگرهای دیگر تراز شود. شبیه‌سازهای عملگر اغلب زمانی استفاده می‌شوند که یک یا چند گلیف برای تشکیل یک عملگر ترکیب می‌شوند، همانند '=='. مقدار پیش‌فرض: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_OperatorEmulator(bool value)=0
```

## توضیحات

مثال:
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_OperatorEmulator(true);
```

## موارد مرتبط

* کلاس [IMathBox](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
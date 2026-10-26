---
title: get_OperatorEmulator()
second_title: "Aspose.Slides برای C++ – مرجع API"
description: "شبیه‌ساز عملگر. وقتی مقدار true باشد، جعبه و محتوای آن همانند یک عملگر واحد رفتار می‌کنند و ویژگی‌های یک عملگر را به ارث می‌برند. این به این معنی است که به‌عنوان مثال، این کاراکتر می‌تواند نقطه‌ای برای شکست خط باشد و می‌تواند به سایر عملگرها تراز شود. شبیه‌سازهای عملگر اغلب هنگامی استفاده می‌شوند که یک یا چند گلیف برای تشکیل یک عملگر ترکیب شوند، مانند '=='. مقدار پیش‌فرض: false"
type: docs
weight: 14
url: /fa/aspose.slides.mathtext/mathbox/get_operatoremulator/
---
## MathBox::get_OperatorEmulator() method

Operator Emulator. وقتی مقدار true باشد، جعبه و محتوای آن همانند یک عملگر واحد رفتار می‌کنند و خصوصیات یک عملگر را به ارث می‌برند. این به این معنی است که به‌عنوان مثال، این کاراکتر می‌تواند نقطه‌ای برای شکست خط باشد و بتواند به عملگرهای دیگر تراز شود. Operator Emulators اغلب وقتی استفاده می‌شوند که یک یا چند glyph برای تشکیل یک عملگر ترکیب شوند، مانند '=='. مقدار پیش‌فرض: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_OperatorEmulator() override
```

## توضیحات

مثال: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
box->set_OperatorEmulator(true);
```

## موارد مرتبط

* کلاس [MathBox](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
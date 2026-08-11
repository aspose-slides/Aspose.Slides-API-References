---
title: set_OperatorEmulator()
second_title: Aspose.Slides برای مرجع API سی++
description: "Operator Emulator. وقتی مقدار true باشد، جعبه و محتویات آن همانند یک عملگر واحد رفتار می‌کنند و خصوصیات یک عملگر را به ارث می‌برند. این به این معنی است که، به عنوان مثال، این کاراکتر می‌تواند به عنوان نقطه‌ای برای شکست خط استفاده شود و می‌تواند با سایر عملگرها هم‌راستا شود. Operator Emulators اغلب زمانی استفاده می‌شوند که یک یا چند گلیف ترکیب شوند تا یک عملگر ایجاد کنند، مانند '=='. مقدار پیش‌فرض: false"
type: docs
weight: 27
url: /fa/aspose.slides.mathtext/mathbox/set_operatoremulator/
---
## MathBox::set_OperatorEmulator(bool) متد


Operator Emulator. وقتی مقدار true باشد، جعبه و محتویات آن همانند یک عملگر واحد رفتار می‌کنند و خصوصیات یک عملگر را به ارث می‌برند. به عنوان مثال، این به این معنی است که این کاراکتر می‌تواند به عنوان نقطه‌ای برای شکست خط عمل کند و می‌تواند با سایر عملگرها هم‌راستا شود. Operator Emulators اغلب زمانی استفاده می‌شوند که یک یا چند گلیف ترکیب شوند تا یک عملگر تشکیل دهند، مانند '=='. مقدار پیش‌فرض: false

```cpp
void Aspose::Slides::MathText::MathBox::set_OperatorEmulator(bool value) override
```

## توضیحات


مثال: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
box->set_OperatorEmulator(true);
```

## موارد مرتبط

* کلاس [MathBox](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
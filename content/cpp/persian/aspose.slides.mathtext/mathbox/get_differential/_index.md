---
title: get_Differential()
second_title: مرجع API Aspose.Slides برای C++
description: "Differential زمانی که true باشد، جعبه به عنوان یک دیفرانسیل عمل می‌کند (مثلاً \\uD835\\uDC51\\uD835\\uDC65 در یک انتگرال)، و فاصله افقی مناسب برای دیفرانسیل ریاضی را دریافت می‌کند. پیش‌فرض: false"
type: docs
weight: 66
url: /fa/aspose.slides.mathtext/mathbox/get_differential/
---
## MathBox::get_Differential() متد

Differential زمانی‌که true باشد، جعبه به‌عنوان یک دیفرانسیل عمل می‌کند (e.g., \\uD835\\uDC51\\uD835\\uDC65 in an integrand)، و فاصله افقی مناسب برای دیفرانسیل ریاضی را دریافت می‌کند. پیش‌فرض: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_Differential() override
```

## توضیحات

مثال:
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## موارد مرتبط

* کلاس [MathBox](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
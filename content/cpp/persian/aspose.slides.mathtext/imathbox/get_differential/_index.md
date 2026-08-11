---
title: get_Differential()
second_title: Aspose.Slides برای مرجع API C++
description: "دیفرانسیل. وقتی مقدار true باشد، جعبه به عنوان یک دیفرانسیل عمل می‌کند (به عنوان مثال، \\uD835\\uDC51\\uD835\\uDC65 در یک انتگرال)، و فاصله افقی مناسب برای دیفرانسیل ریاضی را دریافت می‌کند. پیش‌فرض: false"
type: docs
weight: 66
url: /fa/aspose.slides.mathtext/imathbox/get_differential/
---
## IMathBox::get_Differential() متد

دیفرانسیل. وقتی مقدار true باشد، جعبه به عنوان یک دیفرانسیل عمل می‌کند (به عنوان مثال، \\uD835\\uDC51\\uDC65 در یک انتگرال)، و فاصله افقی مناسب برای دیفرانسیل ریاضی را دریافت می‌کند. پیش‌فرض: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_Differential()=0
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

* کلاس [IMathBox](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
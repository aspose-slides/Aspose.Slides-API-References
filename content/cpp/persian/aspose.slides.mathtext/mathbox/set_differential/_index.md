---
title: set_Differential()
second_title: مرجع API Aspose.Slides برای C++
description: "Differential وقتی مقدار true باشد، جعبه به عنوان یک مشتق عمل می‌کند (به عنوان مثال، \\uD835\\uDC51\\uD835\\uDC65 در یک انتگرال‌گیر) و فاصله افقی مناسب برای مشتق ریاضی را دریافت می‌کند. پیش‌فرض: false"
type: docs
weight: 79
url: /fa/aspose.slides.mathtext/mathbox/set_differential/
---
## MathBox::set_Differential(bool) متد

Differential وقتی مقدار true باشد، جعبه به عنوان یک مشتق عمل می‌کند (به عنوان مثال، \\uD835\\uDC51\\uD835\\uDC65 در یک انتگرال‌گیر)، و فاصله افقی مناسب برای مشتق ریاضی را دریافت می‌کند. پیش‌فرض: false

```cpp
void Aspose::Slides::MathText::MathBox::set_Differential(bool value) override
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
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
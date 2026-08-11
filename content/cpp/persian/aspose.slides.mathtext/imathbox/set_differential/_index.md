---
title: set_Differential()
second_title: Aspose.Slides برای مرجع API C++
description: "مشتق. وقتی true باشد، جعبه به عنوان یک مشتق عمل می‌کند (مثلاً \\uD835\\uDC51\\uD835\\uDC65 در یک انتگرال)، و فاصله افقی مناسب برای مشتق ریاضی را دریافت می‌کند. پیش‌فرض: false"
type: docs
weight: 79
url: /fa/aspose.slides.mathtext/imathbox/set_differential/
---
## IMathBox::set_Differential(bool) متد

مشتق. هنگامی که true باشد، جعبه به عنوان یک مشتق رفتار می‌کند (e.g., \\uD835\\uDC51\\uDC65 in an integrand)، و فاصله افقی مناسب برای مشتق ریاضی را دریافت می‌کند. پیش‌فرض: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_Differential(bool value)=0
```

## توضیحات

مثال: 
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## مراجع مرتبط

* کلاس [IMathBox](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
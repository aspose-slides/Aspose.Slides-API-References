---
title: get_Differential()
second_title: Aspose.Slides مرجع API لـ C++
description: "المشتقة. عندما تكون true، يصبح الصندوق differential (مثال، \\uD835\\uDC51\\uD835\\uDC65 في integrand)، ويتلقى التباعد الأفقي المناسب للمشتقة الرياضية. القيمة الافتراضية: false"
type: docs
weight: 66
url: /ar/aspose.slides.mathtext/imathbox/get_differential/
---
## IMathBox::get_Differential() طريقة

Differential. عندما تكون true، الصندوق يعمل كـ differential (مثال، \\uD835\\uDC51\\uD835\\uDC65 في integrand)، ويتلقى التباعد الأفقي المناسب للمشتقة الرياضية. القيمة الافتراضية: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_Differential()=0
```

## ملاحظات

مثال:
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## أنظر أيضًا

* الفئة [IMathBox](../)
* نطاق الاسم [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)
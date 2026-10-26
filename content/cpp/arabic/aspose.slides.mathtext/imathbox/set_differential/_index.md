---
title: set_Differential()
second_title: مرجع API Aspose.Slides للـ C++
description: "مشتقة. عندما تكون true، يعمل الصندوق كمشتقة (مثال، \\uD835\\uDC51\\uDC65 في تكامل)، ويتلقى التباعد الأفقي المناسب للمشتقة الرياضية. الافتراضي: false"
type: docs
weight: 79
url: /ar/aspose.slides.mathtext/imathbox/set_differential/
---
## IMathBox::set_Differential(bool) طريقة


مشتقة. عندما تكون true، يصبح الصندوق كالمشتقة (مثال، \\uD835\\uDC51\\uD835\\uDC65 في دالة تكاملية)، ويتلقى التباعد الأفقي المناسب للمشتقة الرياضية. الافتراضي: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_Differential(bool value)=0
```

## ملاحظات


مثال: 
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## انظر أيضًا

* الفئة [IMathBox](../)
* النطاق [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)
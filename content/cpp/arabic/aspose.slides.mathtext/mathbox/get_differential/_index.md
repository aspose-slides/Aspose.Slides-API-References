---
title: get_Differential()
second_title: دليل API لـ Aspose.Slides للغة C++
description: "Differential عندما يكون true، يصبح الصندوق تفاضليًا (مثلاً \\uD835\\uDC51\\uD835\\uDC65 في دالة تكامل)، ويتلقى التباعد الأفقي المناسب للتفاضل الرياضي. الافتراضي: false"
type: docs
weight: 66
url: /ar/aspose.slides.mathtext/mathbox/get_differential/
---
## MathBox::get_Differential() طريقة

Differential عندما يكون true، يصبح الصندوق تفاضليًا (مثلاً \\uD835\\uDC51\\uD835\\uDC65 في دالة تكامل)، ويتلقى التباعد الأفقي المناسب للتفاضل الرياضي. الافتراضي: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_Differential() override
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

* فئة [MathBox](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)
---
title: set_Differential()
second_title: Aspose.Slides لـ C++ مرجع API
description: "تفاضل عندما تكون true، يعمل الصندوق كتفاضل (على سبيل المثال، \\uD835\\uDC51\\uD835\\uDC65 في المتكامل)، ويتلقى التباعد الأفقي المناسب للتفاضل الرياضي. القيمة الافتراضية: false"
type: docs
weight: 79
url: /ar/aspose.slides.mathtext/mathbox/set_differential/
---
## MathBox::set_Differential(bool) طريقة

تفاضل عندما true، يصبح الصندوق تفاضلًا (على سبيل المثال، \\uD835\\uDC51\\uD835\\uDC65 في المتكامل)، ويتلقى التباعد الأفقي المناسب للتفاضل الرياضي. القيمة الافتراضية: false

```cpp
void Aspose::Slides::MathText::MathBox::set_Differential(bool value) override
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
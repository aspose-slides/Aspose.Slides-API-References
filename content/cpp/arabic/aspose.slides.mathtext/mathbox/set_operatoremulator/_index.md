---
title: set_OperatorEmulator()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "محاكي المشغل. عندما تكون true، الصندوق ومحتوياته تتصرف كمشغل واحد وتورث خصائص المشغل. هذا يعني، على سبيل المثال، أن الحرف يمكن أن يكون نقطة لكسر السطر ويمكن محاذاته إلى المشغلات الأخرى. غالبًا ما تُستخدم محاكيات المشغل عندما يتحد حرف أو أكثر لتكوين مشغل، مثل '=='. القيمة الافتراضية: false"
type: docs
weight: 27
url: /ar/aspose.slides.mathtext/mathbox/set_operatoremulator/
---
## MathBox::set_OperatorEmulator(bool) طريقة

محاكي المشغل. عندما تكون true، الصندوق ومحتوياته تتصرف كمشغل واحد وتورث خصائص المشغل. هذا يعني، على سبيل المثال، أن الحرف يمكن أن يكون نقطة لكسر السطر ويمكن محاذاته إلى المشغلات الأخرى. غالبًا ما تُستخدم محاكيات المشغل عندما يتحد حرف أو أكثر لتكوين مشغل، مثل '=='. القيمة الافتراضية: false

```cpp
void Aspose::Slides::MathText::MathBox::set_OperatorEmulator(bool value) override
```

## ملاحظات

مثال:
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
box->set_OperatorEmulator(true);
```

## انظر أيضًا

* فئة [MathBox](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)
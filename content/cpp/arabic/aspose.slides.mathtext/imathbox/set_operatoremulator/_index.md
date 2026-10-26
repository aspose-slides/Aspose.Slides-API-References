---
title: set_OperatorEmulator()
second_title: مرجع API لمكتبة Aspose.Slides للغة C++
description: "محاكي المشغل. عند القيمة true، يصبح الصندوق ومحتوياته ككيان مشغل واحد ويرثان خصائص المشغل. وهذا يعني، على سبيل المثال، أن الحرف يمكن أن يكون نقطة لكسر السطر ويمكن محاذاته مع مشغلات أخرى. غالبًا ما تُستخدم محاكيات المشغل عندما يتحد حرف أو أكثر لتكوين مشغل، مثل '=='. القيمة الافتراضية: false"
type: docs
weight: 27
url: /ar/aspose.slides.mathtext/imathbox/set_operatoremulator/
---
## IMathBox::set_OperatorEmulator(bool) طريقة


محاكي المشغل. عند القيمة true، يصبح الصندوق ومحتوياته ككيان مشغل واحد ويرثان خصائص المشغل. هذا يعني، على سبيل المثال، أن الحرف يمكن أن يكون نقطة لكسر السطر ويمكن محاذاته مع مشغلات أخرى. غالبًا ما يتم استخدام محاكيات المشغل عندما يتحد حرف أو أكثر لتكوين مشغل، مثل '=='. القيمة الافتراضية: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_OperatorEmulator(bool value)=0
```

## ملاحظات


مثال: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_OperatorEmulator(true);
```

## انظر أيضًا

* الفئة [IMathBox](../)
* مساحة الاسم [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)
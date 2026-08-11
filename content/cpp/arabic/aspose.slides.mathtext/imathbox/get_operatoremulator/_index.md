---
title: get_OperatorEmulator()
second_title: Aspose.Slides للـ C++ مرجع API
description: "محاكي المشغل. عندما يكون true، الصندوق ومحتوياته يتصرفان كمشغل واحد ويرثان خصائص المشغل. هذا يعني، على سبيل المثال، أن الحرف يمكن أن يكون نقطة لكسر السطر ويمكن محاذاته إلى مشغلات أخرى. غالبًا ما تُستخدم محاكيات المشغل عندما يتحد حرف أو أكثر لتكوين مشغل، مثل '=='. القيمة الافتراضية: false"
type: docs
weight: 14
url: /ar/aspose.slides.mathtext/imathbox/get_operatoremulator/
---
## IMathBox::get_OperatorEmulator() طريقة

محاكي المشغل. عندما يكون true، يكون الصندوق ومحتوياته ككيان مشغل واحد ويرثان خصائص المشغل. هذا يعني، على سبيل المثال، أن الحرف يمكن أن يعمل كنقطة لكسر السطر ويمكن محاذاته إلى مشغلات أخرى. غالبًا ما تُستخدم محاكيات المشغل عندما يجتمع حرف أو أكثر لتكوين مشغل، مثل '=='. القيمة الافتراضية: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_OperatorEmulator()=0
```

## ملاحظات


مثال: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_OperatorEmulator(true);
```

## انظر أيضًا

* الفئة [IMathBox](../)
* فضاء الاسم [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)
---
title: get_OperatorEmulator()
second_title: Aspose.Slides للـ C++ مرجع API
description: "محاكي العامل. عندما يكون true، يتصرف الصندوق ومحتوياته كعامل واحد ويرثان خصائص العامل. وهذا يعني، على سبيل المثال، أن الحرف يمكن أن يكون نقطة لكسر السطر ويمكن محاذاته مع عوامل أخرى. غالبًا ما تُستخدم محاكيات العامل عندما يتم دمج رمز أو أكثر لتكوين عامل، مثل '=='. القيمة الافتراضية: false"
type: docs
weight: 14
url: /ar/aspose.slides.mathtext/mathbox/get_operatoremulator/
---
## MathBox::get_OperatorEmulator() طريقة

Operator Emulator. عندما يكون true، الصندوق ومحتوياته يتصرفان كعامل واحد ويرثان خصائص عامل. هذا يعني، على سبيل المثال، أن الحرف يمكن أن يكون نقطة لكسر السطر ويمكن محاذاته إلى عوامل أخرى. غالبًا ما تُستخدم محاكيات العامل عندما يتم دمج رمز أو أكثر لتشكيل عامل، مثل '=='. القيمة الافتراضية: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_OperatorEmulator() override
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
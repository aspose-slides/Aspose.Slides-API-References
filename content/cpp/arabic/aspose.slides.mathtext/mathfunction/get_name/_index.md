---
title: get_Name()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: اسم الدالة على سبيل المثال، أسماء الدوال هي sin و cos
type: docs
weight: 1
url: /ar/aspose.slides.mathtext/mathfunction/get_name/
---
## MathFunction::get_Name() طريقة

اسم الدالة على سبيل المثال، أسماء الدوال هي sin و cos

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Name() override
```

## ملاحظات

مثال:
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto funcName = func->get_Name();
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* صنف [IMathElement](../../imathelement/)
* صنف [MathFunction](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)
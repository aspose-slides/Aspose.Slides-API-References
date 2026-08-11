---
title: get_Name()
second_title: Aspose.Slides مرجع API للغة C++
description: اسم الدالة على سبيل المثال، أسماء الدوال هي sin و cos
type: docs
weight: 1
url: /ar/aspose.slides.mathtext/imathfunction/get_name/
---
## IMathFunction::get_Name() طريقة

اسم الدالة على سبيل المثال، أسماء الدوال هي sin و cos

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Name()=0
```

## ملاحظات

مثال: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto funcName = func->get_Name();
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* الفئة [IMathElement](../../imathelement/)
* الفئة [IMathFunction](../)
* مساحة الاسم [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)
---
title: get_Subscript()
second_title: مرجع API ل Aspose.Slides للغة C++
description: يحدد معامل الفهرس الفرعي الذي، على سبيل المثال، في حالة عدد صحيح، يضع الحد الأدنى
type: docs
weight: 14
url: /ar/aspose.slides.mathtext/mathnaryoperator/get_subscript/
---
## MathNaryOperator::get_Subscript() طريقة

يحدد معامل الفهرس الفرعي الذي، على سبيل المثال، في حالة عدد صحيح، يضع الحد الأدنى

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Subscript() override
```

## ملاحظات

مثال:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto subscriptArg = naryOperator->get_Subscript();
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathNaryOperator](../)
* مساحة الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)
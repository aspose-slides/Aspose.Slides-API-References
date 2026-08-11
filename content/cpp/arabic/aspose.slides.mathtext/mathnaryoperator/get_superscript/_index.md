---
title: get_Superscript()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد معامل supersript الذي، على سبيل المثال، في حالة التكامل، يحدد الحد العلوي
type: docs
weight: 27
url: /ar/aspose.slides.mathtext/mathnaryoperator/get_superscript/
---
## MathNaryOperator::get_Superscript() طريقة

يحدد معامل supersript الذي، على سبيل المثال، في حالة التكامل، يحدد الحد العلوي

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Superscript() override
```
## ملاحظات

مثال: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto superscriptArg = naryOperator->get_Superscript();
```
## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathNaryOperator](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)
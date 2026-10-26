---
title: get_Superscript()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد معاملًا للمرتبة العلوية، على سبيل المثال، في حالة التكامل، يحدد الحد العلوي
type: docs
weight: 27
url: /ar/aspose.slides.mathtext/imathnaryoperator/get_superscript/
---
## IMathNaryOperator::get_Superscript() طريقة

يحدد معامل مؤشر علوي، على سبيل المثال، في حالة التكامل، يحدد الحد العلوي

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Superscript()=0
```

## ملاحظات

مثال:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto superscriptArg = naryOperator->get_Superscript();
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [IMathNaryOperator](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)
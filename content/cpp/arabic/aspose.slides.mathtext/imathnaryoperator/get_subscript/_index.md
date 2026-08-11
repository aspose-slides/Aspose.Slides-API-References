---
title: get_Subscript()
second_title: Aspose.Slides لمرجع واجهة برمجة التطبيقات C++
description: يحدد معامل المؤشر الفرعي الذي، على سبيل المثال، في حالة التكامل، يحدد الحد الأدنى
type: docs
weight: 14
url: /ar/aspose.slides.mathtext/imathnaryoperator/get_subscript/
---
## IMathNaryOperator::get_Subscript() طريقة

يحدد معامل المؤشر الفرعي الذي، على سبيل المثال، في حالة التكامل، يحدد الحد الأدنى

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Subscript()=0
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
* فئة [IMathNaryOperator](../)
* مساحة اسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)
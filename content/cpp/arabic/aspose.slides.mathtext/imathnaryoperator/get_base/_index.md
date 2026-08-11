---
title: get_Base()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: معامل Base
type: docs
weight: 1
url: /ar/aspose.slides.mathtext/imathnaryoperator/get_base/
---
## IMathNaryOperator::get_Base() طريقة

Base المعامل

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Base()=0
```

## ملاحظات

مثال: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto baseArg = naryOperator->get_Base();
```

## انظر أيضًا

* تعريف_نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [IMathNaryOperator](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)
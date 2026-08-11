---
title: get_Base()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: معامل Base
type: docs
weight: 1
url: /ar/aspose.slides.mathtext/mathnaryoperator/get_base/
---
## MathNaryOperator::get_Base() طريقة

معامل Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Base() override
```

## ملاحظات

مثال:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto baseArg = naryOperator->get_Base();
```

## انظر أيضاً
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathNaryOperator](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)
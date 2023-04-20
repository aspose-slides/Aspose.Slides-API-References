---
title: get_Subscript()
second_title: Aspose.Slides for C++ API Reference
description: Specifies a subscript argument that, for example, in the case of an integral, sets the lower limit
type: docs
weight: 14
url: /cpp/aspose.slides.mathtext/imathnaryoperator/get_subscript/
---
## IMathNaryOperator::get_Subscript() method


Specifies a subscript argument that, for example, in the case of an integral, sets the lower limit

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Subscript()=0
```

## Remarks


Example: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto subscriptArg = naryOperator->get_Subscript();
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [IMathNaryOperator](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
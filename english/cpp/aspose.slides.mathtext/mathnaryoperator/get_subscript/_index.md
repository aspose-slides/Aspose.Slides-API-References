---
title: get_Subscript()
second_title: Aspose.Slides for C++ API Reference
description: Specifies a subscript argument that, for example, in the case of an integral, sets the lower limit
type: docs
weight: 14
url: /cpp/aspose.slides.mathtext/mathnaryoperator/get_subscript/
---
## MathNaryOperator::get_Subscript() method


Specifies a subscript argument that, for example, in the case of an integral, sets the lower limit

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Subscript() override
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
* Class [MathNaryOperator](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
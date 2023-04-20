---
title: get_Superscript()
second_title: Aspose.Slides for C++ API Reference
description: Specifies a supersript argument that, for example, in the case of an integral, sets the upper limit
type: docs
weight: 27
url: /cpp/aspose.slides.mathtext/imathnaryoperator/get_superscript/
---
## IMathNaryOperator::get_Superscript() method


Specifies a supersript argument that, for example, in the case of an integral, sets the upper limit

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Superscript()=0
```

## Remarks


Example: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto superscriptArg = naryOperator->get_Superscript();
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [IMathNaryOperator](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
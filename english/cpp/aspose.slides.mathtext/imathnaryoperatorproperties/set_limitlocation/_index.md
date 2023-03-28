---
title: set_LimitLocation()
second_title: Aspose.Slides for C++ API Reference
description: The location of limits (subscript and superscript)
type: docs
weight: 40
url: /cpp/aspose.slides.mathtext/imathnaryoperatorproperties/set_limitlocation/
---
## IMathNaryOperatorProperties::set_LimitLocation([MathLimitLocations](../../mathlimitlocations/)) method


The location of limits (subscript and superscript)

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_LimitLocation(MathLimitLocations value)=0
```

## Remarks


Example: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## See Also

* Enum [MathLimitLocations](../../mathlimitlocations/)
* Class [IMathNaryOperatorProperties](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)

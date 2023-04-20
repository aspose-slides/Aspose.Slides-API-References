---
title: get_Operator()
second_title: Aspose.Slides for C++ API Reference
description: "Nary Operator Character For example: '\\u2211', '\\u222B'"
type: docs
weight: 1
url: /cpp/aspose.slides.mathtext/imathnaryoperatorproperties/get_operator/
---
## IMathNaryOperatorProperties::get_Operator() method


Nary Operator Character For example: '\\u2211', '\\u222B'

```cpp
virtual char16_t Aspose::Slides::MathText::IMathNaryOperatorProperties::get_Operator()=0
```

## Remarks


Example: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## See Also

* Class [IMathNaryOperatorProperties](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
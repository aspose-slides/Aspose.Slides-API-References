---
title: set_Operator()
second_title: Aspose.Slides for C++ API Reference
description: "Nary Operator Character For example: '\\u2211', '\\u222B'"
type: docs
weight: 53
url: /cpp/aspose.slides.mathtext/mathnaryoperator/set_operator/
---
## MathNaryOperator::set_Operator(char16_t) method


Nary Operator Character For example: '\\u2211', '\\u222B'

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_Operator(char16_t value) override
```

## Remarks


Example: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## See Also

* Class [MathNaryOperator](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
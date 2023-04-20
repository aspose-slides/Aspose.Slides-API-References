---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides for C++ API Reference
description: Operator Character grows vertically to match its operand height
type: docs
weight: 53
url: /cpp/aspose.slides.mathtext/imathnaryoperatorproperties/get_growtomatchoperandheight/
---
## IMathNaryOperatorProperties::get_GrowToMatchOperandHeight() method


Operator Character grows vertically to match its operand height

```cpp
virtual bool Aspose::Slides::MathText::IMathNaryOperatorProperties::get_GrowToMatchOperandHeight()=0
```

## Remarks


Example: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## See Also

* Class [IMathNaryOperatorProperties](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
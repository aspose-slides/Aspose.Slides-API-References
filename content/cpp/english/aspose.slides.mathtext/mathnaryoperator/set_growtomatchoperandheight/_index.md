---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides for C++ API Reference
description: Operator Character grows vertically to match its operand height
type: docs
weight: 105
url: /aspose.slides.mathtext/mathnaryoperator/set_growtomatchoperandheight/
---
## MathNaryOperator::set_GrowToMatchOperandHeight(bool) method


Operator Character grows vertically to match its operand height

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_GrowToMatchOperandHeight(bool value) override
```

## Remarks


Example: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## See Also

* Class [MathNaryOperator](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
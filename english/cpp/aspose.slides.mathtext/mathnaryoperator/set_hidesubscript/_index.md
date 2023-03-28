---
title: set_HideSubscript()
second_title: Aspose.Slides for C++ API Reference
description: Hide Subscript
type: docs
weight: 131
url: /cpp/aspose.slides.mathtext/mathnaryoperator/set_hidesubscript/
---
## MathNaryOperator::set_HideSubscript(**bool**) method


Hide Subscript

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_HideSubscript(bool value) override
```

## Remarks


Example: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSubscript(true);
```

## See Also

* Class [MathNaryOperator](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)

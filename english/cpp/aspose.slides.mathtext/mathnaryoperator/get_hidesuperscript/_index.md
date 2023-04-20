---
title: get_HideSuperscript()
second_title: Aspose.Slides for C++ API Reference
description: Hide Superscript
type: docs
weight: 144
url: /cpp/aspose.slides.mathtext/mathnaryoperator/get_hidesuperscript/
---
## MathNaryOperator::get_HideSuperscript() method


Hide Superscript

```cpp
bool Aspose::Slides::MathText::MathNaryOperator::get_HideSuperscript() override
```

## Remarks


Example: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSuperscript(true);
```

## See Also

* Class [MathNaryOperator](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
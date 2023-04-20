---
title: set_HideSuperscript()
second_title: Aspose.Slides for C++ API Reference
description: Hide Superscript
type: docs
weight: 118
url: /cpp/aspose.slides.mathtext/imathnaryoperatorproperties/set_hidesuperscript/
---
## IMathNaryOperatorProperties::set_HideSuperscript(bool) method


Hide Superscript

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_HideSuperscript(bool value)=0
```

## Remarks


Example: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSuperscript(true);
```

## See Also

* Class [IMathNaryOperatorProperties](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
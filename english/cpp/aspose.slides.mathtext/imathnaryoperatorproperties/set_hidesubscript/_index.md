---
title: set_HideSubscript()
second_title: Aspose.Slides for C++ API Reference
description: Hide Subscript
type: docs
weight: 92
url: /cpp/aspose.slides.mathtext/imathnaryoperatorproperties/set_hidesubscript/
---
## IMathNaryOperatorProperties::set_HideSubscript(bool) method


Hide Subscript

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_HideSubscript(bool value)=0
```

## Remarks


Example: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSubscript(true);
```

## See Also

* Class [IMathNaryOperatorProperties](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
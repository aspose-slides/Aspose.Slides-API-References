---
title: get_HideSubscript()
second_title: Aspose.Slides for C++ API Reference
description: Hide Subscript
type: docs
weight: 79
url: /cpp/aspose.slides.mathtext/imathnaryoperatorproperties/get_hidesubscript/
---
## IMathNaryOperatorProperties::get_HideSubscript() method


Hide Subscript

```cpp
virtual bool Aspose::Slides::MathText::IMathNaryOperatorProperties::get_HideSubscript()=0
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
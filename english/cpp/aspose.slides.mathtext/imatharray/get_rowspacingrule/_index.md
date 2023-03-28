---
title: get_RowSpacingRule()
second_title: Aspose.Slides for C++ API Reference
description: The type of vertical spacing between array elements
type: docs
weight: 92
url: /cpp/aspose.slides.mathtext/imatharray/get_rowspacingrule/
---
## IMathArray::get_RowSpacingRule() method


The type of vertical spacing between array elements

```cpp
virtual MathRowSpacingRule Aspose::Slides::MathText::IMathArray::get_RowSpacingRule()=0
```

## Remarks


Example: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::OneAndAHalfLineGap);
```

## See Also

* Enum [MathRowSpacingRule](../../mathrowspacingrule/)
* Class [IMathArray](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)

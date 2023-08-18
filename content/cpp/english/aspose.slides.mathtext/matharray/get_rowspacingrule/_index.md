---
title: get_RowSpacingRule()
second_title: Aspose.Slides for C++ API Reference
description: "The type of vertical spacing between array elements Default: SingleLineGap"
type: docs
weight: 92
url: /aspose.slides.mathtext/matharray/get_rowspacingrule/
---
## MathArray::get_RowSpacingRule() method


The type of vertical spacing between array elements Default: SingleLineGap

```cpp
MathRowSpacingRule Aspose::Slides::MathText::MathArray::get_RowSpacingRule() override
```

## Remarks


Example: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::OneAndAHalfLineGap);
```

## See Also

* Enum [MathRowSpacingRule](../../mathrowspacingrule/)
* Class [MathArray](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
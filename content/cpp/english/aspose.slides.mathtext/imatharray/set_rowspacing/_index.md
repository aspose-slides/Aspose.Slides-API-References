---
title: set_RowSpacing()
second_title: Aspose.Slides for C++ API Reference
description: "Spacing between rows of an array It is used only when RowSpacingRule is set to 3 Exactly in which case the unit of measure is points or Multiple in which case the unit of measure is half-lines. Default: 0"
type: docs
weight: 131
url: /aspose.slides.mathtext/imatharray/set_rowspacing/
---
## IMathArray::set_RowSpacing(uint32_t) method


Spacing between rows of an array It is used only when RowSpacingRule is set to 3 Exactly in which case the unit of measure is points or Multiple in which case the unit of measure is half-lines. Default: 0

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_RowSpacing(uint32_t value)=0
```

## Remarks


Example: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## See Also

* Class [IMathArray](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
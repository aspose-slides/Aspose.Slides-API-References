---
title: set_Position()
second_title: Aspose.Slides for C++ API Reference
description: "Position of grouping character. Default: Bottom"
type: docs
weight: 53
url: /aspose.slides.mathtext/imathgroupingcharacter/set_position/
---
## IMathGroupingCharacter::set_Position(MathTopBotPositions) method


Position of grouping character. Default: Bottom

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_Position(MathTopBotPositions value)=0
```

## Remarks


Example: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Position(MathTopBotPositions::Top);
```

## See Also

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Class [IMathGroupingCharacter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
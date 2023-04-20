---
title: set_Position()
second_title: Aspose.Slides for C++ API Reference
description: "Position of grouping character. Default: Bottom"
type: docs
weight: 53
url: /cpp/aspose.slides.mathtext/mathgroupingcharacter/set_position/
---
## MathGroupingCharacter::set_Position(MathTopBotPositions) method


Position of grouping character. Default: Bottom

```cpp
void Aspose::Slides::MathText::MathGroupingCharacter::set_Position(MathTopBotPositions value) override
```

## Remarks


Example: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Position(MathTopBotPositions::Top);
```

## See Also

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Class [MathGroupingCharacter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
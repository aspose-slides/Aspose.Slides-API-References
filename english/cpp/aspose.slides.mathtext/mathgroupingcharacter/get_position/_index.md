---
title: get_Position()
second_title: Aspose.Slides for C++ API Reference
description: "Position of grouping character. Default: Bottom"
type: docs
weight: 40
url: /cpp/aspose.slides.mathtext/mathgroupingcharacter/get_position/
---
## MathGroupingCharacter::get_Position() method


Position of grouping character. Default: Bottom

```cpp
MathTopBotPositions Aspose::Slides::MathText::MathGroupingCharacter::get_Position() override
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
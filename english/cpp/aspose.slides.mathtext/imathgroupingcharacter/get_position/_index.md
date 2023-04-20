---
title: get_Position()
second_title: Aspose.Slides for C++ API Reference
description: "Position of grouping character. Default: Bottom"
type: docs
weight: 40
url: /cpp/aspose.slides.mathtext/imathgroupingcharacter/get_position/
---
## IMathGroupingCharacter::get_Position() method


Position of grouping character. Default: Bottom

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathGroupingCharacter::get_Position()=0
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
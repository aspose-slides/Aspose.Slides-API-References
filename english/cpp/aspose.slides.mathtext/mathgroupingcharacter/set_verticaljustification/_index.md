---
title: set_VerticalJustification()
second_title: Aspose.Slides for C++ API Reference
description: "Vertical justification of group character. Specifies the alignment of the object with respect to the baseline. For example, when the group character is above the object, VerticalJustification of Top signifies that the top of the object falls on the baseline; when VerticalJustification is set to Bottom, the bottom of the object is on the baseline Default: Bottom for Position=Top, and Top for Position=Bottom"
type: docs
weight: 79
url: /cpp/aspose.slides.mathtext/mathgroupingcharacter/set_verticaljustification/
---
## MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) method


Vertical justification of group character. Specifies the alignment of the object with respect to the baseline. For example, when the group character is above the object, VerticalJustification of Top signifies that the top of the object falls on the baseline; when VerticalJustification is set to Bottom, the bottom of the object is on the baseline Default: Bottom for Position=Top, and Top for Position=Bottom

```cpp
void Aspose::Slides::MathText::MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value) override
```

## Remarks


Example: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## See Also

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Class [MathGroupingCharacter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
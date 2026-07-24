---
title: get_Position()
second_title: Aspose.Slides für C++ API-Referenz
description: "Position des Gruppierungszeichens. Standard: Unten"
type: docs
weight: 40
url: /de/aspose.slides.mathtext/imathgroupingcharacter/get_position/
---
## IMathGroupingCharacter::get_Position() Methode


Position des Gruppierungszeichens. Standard: Unten

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathGroupingCharacter::get_Position()=0
```

## Hinweise


Beispiel: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Position(MathTopBotPositions::Top);
```

## Siehe auch

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Klasse [IMathGroupingCharacter](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
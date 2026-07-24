---
title: get_Position()
second_title: Aspose.Slides für C++ API-Referenz
description: "Position des Gruppierungszeichens. Standard: Unten"
type: docs
weight: 40
url: /de/aspose.slides.mathtext/mathgroupingcharacter/get_position/
---
## MathGroupingCharacter::get_Position() Methode


Position des Gruppierungszeichens. Standard: Unten

```cpp
MathTopBotPositions Aspose::Slides::MathText::MathGroupingCharacter::get_Position() override
```

## Anmerkungen


Beispiel: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Position(MathTopBotPositions::Top);
```

## Siehe auch

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Klasse [MathGroupingCharacter](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)
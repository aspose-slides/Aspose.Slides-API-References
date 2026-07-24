---
title: set_Position()
second_title: Aspose.Slides für C++ API-Referenz
description: "Position des Gruppierungszeichens. Standard: Bottom"
type: docs
weight: 53
url: /de/aspose.slides.mathtext/imathgroupingcharacter/set_position/
---
## IMathGroupingCharacter::set_Position(MathTopBotPositions) Methode


Position des Gruppierungszeichens. Standard: Bottom

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_Position(MathTopBotPositions value)=0
```

## Anmerkungen


Beispiel: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Position(MathTopBotPositions::Top);
```

## Siehe auch

* Aufzählung [MathTopBotPositions](../../mathtopbotpositions/)
* Klasse [IMathGroupingCharacter](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)
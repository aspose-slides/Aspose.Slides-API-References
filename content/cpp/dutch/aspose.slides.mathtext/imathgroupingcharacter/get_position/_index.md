---
title: get_Position()
second_title: Aspose.Slides voor C++ API-referentie
description: "Positie van groeperingsteken. Standaard: Onder"
type: docs
weight: 40
url: /nl/aspose.slides.mathtext/imathgroupingcharacter/get_position/
---
## IMathGroupingCharacter::get_Position() methode


Positie van groeperingsteken. Standaard: Onder

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathGroupingCharacter::get_Position()=0
```

## Opmerkingen


Voorbeeld: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Position(MathTopBotPositions::Top);
```

## Zie ook

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Klasse [IMathGroupingCharacter](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)
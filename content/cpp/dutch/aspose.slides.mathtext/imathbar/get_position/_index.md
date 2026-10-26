---
title: get_Position()
second_title: Aspose.Slides voor C++ API-referentie
description: "Positie van de balklijn. Standaard: Boven"
type: docs
weight: 14
url: /nl/aspose.slides.mathtext/imathbar/get_position/
---
## IMathBar::get_Position() methode


Positie van de balklijn. Standaard: Boven

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathBar::get_Position()=0
```

## Opmerkingen


Voorbeeld: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
mathBar->set_Position(MathTopBotPositions::Bottom);
```

## Zie ook

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Klasse [IMathBar](../)
* Namespace [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)
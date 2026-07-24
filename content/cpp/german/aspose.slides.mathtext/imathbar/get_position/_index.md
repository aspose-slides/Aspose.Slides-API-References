---
title: get_Position()
second_title: Aspose.Slides für C++ API Referenz
description: "Position der Balkenlinie. Standard: Oben"
type: docs
weight: 14
url: /de/aspose.slides.mathtext/imathbar/get_position/
---
## IMathBar::get_Position() Methode


Position der Balkenlinie. Standard: Oben

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathBar::get_Position()=0
```

## Hinweise


Beispiel: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
mathBar->set_Position(MathTopBotPositions::Bottom);
```

## Siehe auch

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Klasse [IMathBar](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)
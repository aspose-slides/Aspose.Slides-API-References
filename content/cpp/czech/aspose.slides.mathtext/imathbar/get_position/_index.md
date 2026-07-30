---
title: get_Position()
second_title: Aspose.Slides pro C++ API Reference
description: "Pozice čáry pruhu. Výchozí: Horní"
type: docs
weight: 14
url: /cs/aspose.slides.mathtext/imathbar/get_position/
---
## IMathBar::get_Position() metoda


Pozice čáry pruhu. Výchozí: Horní

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathBar::get_Position()=0
```

## Poznámky


Příklad: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
mathBar->set_Position(MathTopBotPositions::Bottom);
```

## Viz také

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* třída [IMathBar](../)
* jmenný prostor [Aspose::Slides::MathText](../../)
* knihovna [Aspose.Slides](../../../)
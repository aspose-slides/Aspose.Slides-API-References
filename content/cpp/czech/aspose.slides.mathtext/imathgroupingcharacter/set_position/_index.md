---
title: set_Position()
second_title: Aspose.Slides pro C++ API Reference
description: "Pozice seskupovacího znaku. Výchozí: Bottom"
type: docs
weight: 53
url: /cs/aspose.slides.mathtext/imathgroupingcharacter/set_position/
---
## IMathGroupingCharacter::set_Position(MathTopBotPositions) metoda

Pozice seskupovacího znaku. Výchozí: Bottom

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_Position(MathTopBotPositions value)=0
```

## Poznámky

Příklad: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Position(MathTopBotPositions::Top);
```

## Viz také

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Třída [IMathGroupingCharacter](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
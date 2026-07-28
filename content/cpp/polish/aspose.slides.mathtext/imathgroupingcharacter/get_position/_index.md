---
title: get_Position()
second_title: Odwołanie do API Aspose.Slides dla C++
description: "Pozycja znaku grupującego. Domyślnie: Bottom"
type: docs
weight: 40
url: /pl/aspose.slides.mathtext/imathgroupingcharacter/get_position/
---
## IMathGroupingCharacter::get_Position() metoda


Pozycja znaku grupującego. Domyślnie: Bottom

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathGroupingCharacter::get_Position()=0
```

## Uwagi


Przykład:
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Position(MathTopBotPositions::Top);
```

## Zobacz również

* Wyliczenie [MathTopBotPositions](../../mathtopbotpositions/)
* Klasa [IMathGroupingCharacter](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)
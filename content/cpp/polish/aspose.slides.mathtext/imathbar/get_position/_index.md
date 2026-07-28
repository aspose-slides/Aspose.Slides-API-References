---
title: get_Position()
second_title: Referencja API Aspose.Slides dla C++
description: "Pozycja linii belki. Domyślnie: Góra"
type: docs
weight: 14
url: /pl/aspose.slides.mathtext/imathbar/get_position/
---
## IMathBar::get_Position() metoda


Pozycja linii belki. Domyślnie: Góra

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathBar::get_Position()=0
```

## Uwagi


Przykład: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
mathBar->set_Position(MathTopBotPositions::Bottom);
```

## Zobacz także

* Wyliczenie [MathTopBotPositions](../../mathtopbotpositions/)
* Klasa [IMathBar](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)
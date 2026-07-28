---
title: set_VerticalJustification()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: "Pionowe wyrównanie znaku grupy. Określa wyrównanie obiektu względem linii bazowej. Na przykład, gdy znak grupy znajduje się nad obiektem, VerticalJustification of Top oznacza, że górna część obiektu znajduje się na linii bazowej; gdy VerticalJustification jest ustawione na Bottom, dolna część obiektu znajduje się na linii bazowej. Domyślnie: Bottom dla Position=Top oraz Top dla Position=Bottom"
type: docs
weight: 79
url: /pl/aspose.slides.mathtext/imathgroupingcharacter/set_verticaljustification/
---
## IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) metoda

Pionowe wyrównanie znaku grupy. Określa wyrównanie obiektu względem linii bazowej. Na przykład, gdy znak grupy znajduje się nad obiektem, VerticalJustification of Top oznacza, że górna część obiektu znajduje się na linii bazowej; gdy VerticalJustification jest ustawione na Bottom, dolna część obiektu znajduje się na linii bazowej. Domyślnie: Bottom dla Position=Top i Top dla Position=Bottom

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value)=0
```

## Uwagi


Przykład: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## Zobacz także

* Wyliczenie [MathTopBotPositions](../../mathtopbotpositions/)
* Klasa [IMathGroupingCharacter](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)
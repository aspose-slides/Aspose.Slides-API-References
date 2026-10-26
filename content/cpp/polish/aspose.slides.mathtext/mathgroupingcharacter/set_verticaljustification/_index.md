---
title: set_VerticalJustification()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: "Pionowe wyrównanie znaku grupy. Określa wyrównanie obiektu względem linii bazowej. Na przykład, gdy znak grupy znajduje się nad obiektem, VerticalJustification ustawione na Top oznacza, że górna część obiektu znajduje się na linii bazowej; gdy VerticalJustification jest ustawione na Bottom, dolna część obiektu znajduje się na linii bazowej. Domyślnie: Bottom dla Position=Top oraz Top dla Position=Bottom"
type: docs
weight: 79
url: /pl/aspose.slides.mathtext/mathgroupingcharacter/set_verticaljustification/
---
## MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) metoda

Pionowe wyrównanie znaku grupy. Określa wyrównanie obiektu względem linii bazowej. Na przykład, gdy znak grupy znajduje się nad obiektem, VerticalJustification ustawione na Top oznacza, że górna krawędź obiektu znajduje się na linii bazowej; gdy VerticalJustification jest ustawione na Bottom, dolna krawędź obiektu znajduje się na linii bazowej. Domyślnie: Bottom dla Position=Top oraz Top dla Position=Bottom

```cpp
void Aspose::Slides::MathText::MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value) override
```

## Uwagi


Przykład: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## Zobacz także

* Wyliczenie [MathTopBotPositions](../../mathtopbotpositions/)
* Klasa [MathGroupingCharacter](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)
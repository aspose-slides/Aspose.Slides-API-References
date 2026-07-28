---
title: get_VerticalJustification()
second_title: Aspose.Slides dla C++ - odniesienie API
description: "Pionowe justowanie znaku grupy. Określa wyrównanie obiektu względem linii bazowej. Na przykład, gdy znak grupy znajduje się nad obiektem, ustawienie VerticalJustification na Top oznacza, że górna część obiektu leży na linii bazowej; gdy VerticalJustification jest ustawione na Bottom, dolna część obiektu znajduje się na linii bazowej. Domyślnie: Bottom dla Position=Top oraz Top dla Position=Bottom"
type: docs
weight: 66
url: /pl/aspose.slides.mathtext/mathgroupingcharacter/get_verticaljustification/
---
## MathGroupingCharacter::get_VerticalJustification() metoda

Pionowe justowanie znaku grupy. Określa wyrównanie obiektu względem linii bazowej. Na przykład, gdy znak grupy znajduje się nad obiektem, VerticalJustification ustawione na Top oznacza, że górna część obiektu leży na linii bazowej; gdy VerticalJustification jest ustawione na Bottom, dolna część obiektu znajduje się na linii bazowej. Domyślnie: Bottom dla Position=Top oraz Top dla Position=Bottom

```cpp
MathTopBotPositions Aspose::Slides::MathText::MathGroupingCharacter::get_VerticalJustification() override
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
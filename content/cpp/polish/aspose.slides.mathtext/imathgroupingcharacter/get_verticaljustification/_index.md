---
title: get_VerticalJustification()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Justowanie pionowe znaku grupowego. Określa wyrównanie obiektu względem linii bazowej. Na przykład, gdy znak grupowy znajduje się powyżej obiektu, VerticalJustification ustawione na Top oznacza, że górna część obiektu znajduje się na linii bazowej; gdy VerticalJustification jest ustawione na Bottom, dolna część obiektu znajduje się na linii bazowej Domyślnie: Bottom for Position=Top, oraz Top for Position=Bottom"
type: docs
weight: 66
url: /pl/aspose.slides.mathtext/imathgroupingcharacter/get_verticaljustification/
---
## IMathGroupingCharacter::get_VerticalJustification() metoda

Justowanie pionowe znaku grupowego. Określa wyrównanie obiektu względem linii bazowej. Na przykład, gdy znak grupowy znajduje się powyżej obiektu, VerticalJustification ustawione na Top oznacza, że górna część obiektu znajduje się na linii bazowej; gdy VerticalJustification jest ustawione na Bottom, dolna część obiektu znajduje się na linii bazowej Domyślne: Bottom dla Position=Top oraz Top dla Position=Bottom

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathGroupingCharacter::get_VerticalJustification()=0
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
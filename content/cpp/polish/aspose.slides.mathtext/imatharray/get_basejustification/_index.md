---
title: get_BaseJustification()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Określa wyrównanie tablicy względem otaczającego tekstu. Tekst poza tablicą może być wyrównany do dołu, do góry lub do środka obiektu tablicy. Domyślna wartość: Center"
type: docs
weight: 14
url: /pl/aspose.slides.mathtext/imatharray/get_basejustification/
---
## IMathArray::get_BaseJustification() metoda

Określa wyrównanie tablicy względem otaczającego tekstu. Tekst poza tablicą może być wyrównany do dołu, do góry lub do środka obiektu tablicy. Wartość domyślna: Center

```cpp
virtual MathVerticalAlignment Aspose::Slides::MathText::IMathArray::get_BaseJustification()=0
```

## Uwagi

Przykład: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## Zobacz także

* Wyliczenie [MathVerticalAlignment](../../mathverticalalignment/)
* Klasa [IMathArray](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)
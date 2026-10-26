---
title: get_BaseJustification()
second_title: "Aspose.Slides dla C++ – Dokumentacja API"
description: "Określa wyrównanie tablicy względem otaczającego tekstu. Tekst znajdujący się poza tablicą może być wyrównany do dołu, góry lub środka obiektu tablicy. Domyślna wartość: Center"
type: docs
weight: 14
url: /pl/aspose.slides.mathtext/matharray/get_basejustification/
---
## MathArray::get_BaseJustification() metoda

Określa wyrównanie tablicy względem otaczającego tekstu. Tekst znajdujący się poza tablicą może być wyrównany do dołu, góry lub środka obiektu tablicy. Default value: Center

```cpp
MathVerticalAlignment Aspose::Slides::MathText::MathArray::get_BaseJustification() override
```

## Uwagi

Example: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## Zobacz także

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Klasa [MathArray](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)
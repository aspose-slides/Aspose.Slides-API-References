---
title: set_BaseJustification()
second_title: Aspose.Slides for C++ – odniesienie API
description: "Określa wyrównanie tablicy względem otaczającego tekstu. Tekst znajdujący się poza tablicą może być wyrównany do dołu, góry lub środka obiektu tablicy. Domyślna wartość: Center"
type: docs
weight: 27
url: /pl/aspose.slides.mathtext/matharray/set_basejustification/
---
## MathArray::set_BaseJustification(MathVerticalAlignment) metoda


Określa wyrównanie tablicy względem otaczającego tekstu. Tekst znajdujący się poza tablicą może być wyrównany do dołu, góry lub środka obiektu tablicy. Domyślna wartość: Center

```cpp
void Aspose::Slides::MathText::MathArray::set_BaseJustification(MathVerticalAlignment value) override
```

## Uwagi


Przykład: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## Zobacz także

* Wyliczenie [MathVerticalAlignment](../../mathverticalalignment/)
* Klasa [MathArray](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)
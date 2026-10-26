---
title: set_BaseJustification()
second_title: Aspose.Slides dla C++ - odniesienie API
description: "Określa wyrównanie tablicy względem otaczającego tekstu. Tekst znajdujący się poza tablicą może być wyrównany do dołu, góry lub środka obiektu tablicy. Domyślna wartość: Center"
type: docs
weight: 27
url: /pl/aspose.slides.mathtext/imatharray/set_basejustification/
---
## IMathArray::set_BaseJustification(MathVerticalAlignment) method

Określa wyrównanie tablicy względem otaczającego tekstu. Tekst znajdujący się poza tablicą może być wyrównany do dołu, góry lub środka obiektu tablicy. Domyślna wartość: Center

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_BaseJustification(MathVerticalAlignment value)=0
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
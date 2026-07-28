---
title: get_Arguments()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zestaw elementów tablicy
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/matharray/get_arguments/
---
## MathArray::get_Arguments() metoda


Zestaw elementów tablicy

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathArray::get_Arguments() override
```

## Uwagi


Przykład:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->get_Arguments()->Add(System::MakeObject<MathematicalText>(u"item2"));
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElementCollection](../../imathelementcollection/)
* Klasa [MathArray](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)
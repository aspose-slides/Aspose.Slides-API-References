---
title: get_Arguments()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Zestaw elementów tablicy
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/imatharray/get_arguments/
---
## IMathArray::get_Arguments() metoda

Zestaw elementów tablicy

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathArray::get_Arguments()=0
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
* Klasa [IMathArray](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)
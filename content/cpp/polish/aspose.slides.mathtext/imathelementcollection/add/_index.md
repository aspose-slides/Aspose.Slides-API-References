---
title: Add()
second_title: Aspose.Slides dla C++ – referencja API
description: Dodaje element matematyczny na koniec kolekcji.
type: docs
weight: 27
url: /pl/aspose.slides.mathtext/imathelementcollection/add/
---
## IMathElementCollection::Add(System::SharedPtr\<IMathElement\>) metoda

Dodaje element matematyczny na koniec kolekcji.

```cpp
virtual void Aspose::Slides::MathText::IMathElementCollection::Add(System::SharedPtr<IMathElement> item)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | [IMathElement](../../imathelement/) do dodania na koniec kolekcji. |

## Uwagi



Przykład: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
collection->Add(System::MakeObject<MathematicalText>(u"+"));
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [IMathElementCollection](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)
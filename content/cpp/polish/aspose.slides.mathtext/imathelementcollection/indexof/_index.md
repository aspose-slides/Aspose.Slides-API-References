---
title: IndexOf()
second_title: Aspose.Slides dla C++ – Referencja API
description: Określa indeks określonego elementu matematycznego w kolekcji.
type: docs
weight: 40
url: /pl/aspose.slides.mathtext/imathelementcollection/indexof/
---
## IMathElementCollection::IndexOf(System::SharedPtr\<IMathElement\>) metoda

Określa indeks określonego elementu matematycznego w kolekcji.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathElementCollection::IndexOf(System::SharedPtr<IMathElement> item)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element do znalezienia w kolekcji. |

### Wartość zwracana

Indeks *item* jeśli zostanie znaleziony w kolekcji; w przeciwnym razie -1.
## Uwagi



Przykład: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
int32_t index = collection->IndexOf(plusElement);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [IMathElementCollection](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)
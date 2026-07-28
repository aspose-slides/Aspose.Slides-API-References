---
title: Contains()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Określa, czy kolekcja zawiera określoną wartość.
type: docs
weight: 66
url: /pl/aspose.slides.mathtext/imathblockcollection/contains/
---
## IMathBlockCollection::Contains(System::SharedPtr\<IMathBlock\>) metoda

Określa, czy kolekcja zawiera określoną wartość.

```cpp
virtual bool Aspose::Slides::MathText::IMathBlockCollection::Contains(System::SharedPtr<IMathBlock> item)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Obiekt, który ma zostać odnaleziony w kolekcji. |

### Wartość zwracana

true, jeśli *item*  zostanie znaleziony w kolekcji; w przeciwnym razie false.

## Uwagi



Przykład: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
bool contains = blockCollection->Contains(block);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathBlock](../../imathblock/)
* Klasa [IMathBlockCollection](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)
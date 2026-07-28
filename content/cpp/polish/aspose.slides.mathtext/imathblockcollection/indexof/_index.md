---
title: IndexOf()
second_title: Aspose.Slides dla C++ - odniesienie do API
description: Określa indeks konkretnego IMathBlock w kolekcji.
type: docs
weight: 79
url: /pl/aspose.slides.mathtext/imathblockcollection/indexof/
---
## IMathBlockCollection::IndexOf(System::SharedPtr\<IMathBlock\>) method


Określa indeks konkretnego [IMathBlock](../../imathblock/) w kolekcji.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::IndexOf(System::SharedPtr<IMathBlock> item)=0
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Element do odnalezienia w kolekcji. |

### Wartość zwracana

Indeks *item*  jeśli został znaleziony w kolekcji; w przeciwnym razie -1.
## Uwagi



Przykład: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
int32_t index = blockCollection->IndexOf(block);
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathBlock](../../imathblock/)
* Klasa [IMathBlockCollection](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)
---
title: Insert()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Wstawia IMathBlock do kolekcji pod określonym indeksem.
type: docs
weight: 27
url: /pl/aspose.slides.mathtext/imathblockcollection/insert/
---
## IMathBlockCollection::Insert(int32_t, System::SharedPtr\<IMathBlock\>) metoda


Wstawia [IMathBlock](../../imathblock/) do kolekcji pod wskazanym indeksem.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Insert(int32_t index, System::SharedPtr<IMathBlock> item)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks zerowy, pod którym element ma zostać wstawiony. |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | [IMathBlock](../../imathblock/) do wstawienia. |
## Uwagi



Przykład: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Insert(0, block);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathBlock](../../imathblock/)
* Klasa [IMathBlockCollection](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)
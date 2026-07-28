---
title: Add()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Dodaje IMathBlock na koniec kolekcji.
type: docs
weight: 14
url: /pl/aspose.slides.mathtext/imathblockcollection/add/
---
## IMathBlockCollection::Add(System::SharedPtr\<IMathBlock\>) metoda

Dodaje [IMathBlock](../../imathblock/) na koniec kolekcji.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Add(System::SharedPtr<IMathBlock> item)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Blok matematyczny, który zostanie dodany na koniec kolekcji |
## Uwagi

Przykład:
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathBlock](../../imathblock/)
* Klasa [IMathBlockCollection](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)
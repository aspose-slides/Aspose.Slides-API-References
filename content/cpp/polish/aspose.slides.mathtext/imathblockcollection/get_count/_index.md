---
title: get_Count()
second_title: Aspose.Slides dla C++ – Referencja API
description: Zwraca liczbę elementów faktycznie znajdujących się w kolekcji. Tylko do odczytu int32_t.
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/imathblockcollection/get_count/
---
## IMathBlockCollection::get_Count() metoda

Zwraca liczbę elementów faktycznie znajdujących się w kolekcji. Tylko do odczytu **int32_t**.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::get_Count()=0
```

## Uwagi

Przykład: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
int32_t blocksCount = blockCollection->get_Count();
```

## Zobacz także

* Klasa [IMathBlockCollection](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)
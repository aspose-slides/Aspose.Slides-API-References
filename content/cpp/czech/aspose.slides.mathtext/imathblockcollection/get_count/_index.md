---
title: get_Count()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vrací počet prvků skutečně obsažených ve sbírce. Pouze pro čtení int32_t.
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/imathblockcollection/get_count/
---
## IMathBlockCollection::get_Count() metoda

Vrací počet prvků skutečně obsažených ve sbírce. Pouze pro čtení **int32_t**.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::get_Count()=0
```

## Poznámky


Příklad: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
int32_t blocksCount = blockCollection->get_Count();
```

## Viz také

* Třída [IMathBlockCollection](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)
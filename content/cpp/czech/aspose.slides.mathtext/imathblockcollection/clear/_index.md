---
title: Clear()
second_title: Aspose.Slides pro C++ API Reference
description: Odstraňuje všechny prvky z kolekce.
type: docs
weight: 118
url: /cs/aspose.slides.mathtext/imathblockcollection/clear/
---
## IMathBlockCollection::Clear() metoda

Odstraní všechny prvky z kolekce.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Clear()=0
```

## Poznámky

Příklad:
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
blockCollection->Clear();
```

## Viz také

* Třída [IMathBlockCollection](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)
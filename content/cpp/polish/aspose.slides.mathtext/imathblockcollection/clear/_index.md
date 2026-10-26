---
title: Clear()
second_title: Aspose.Slides dla C++ Referencja API
description: Usuwa wszystkie elementy z kolekcji.
type: docs
weight: 118
url: /pl/aspose.slides.mathtext/imathblockcollection/clear/
---
## IMathBlockCollection::Clear() metoda


Usuwa wszystkie elementy z kolekcji.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Clear()=0
```

## Uwagi


Przykład: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
blockCollection->Clear();
```

## Zobacz także

* Klasa [IMathBlockCollection](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)
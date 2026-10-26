---
title: Clear()
second_title: Riferimento API Aspose.Slides per C++
description: Rimuove tutti gli elementi dalla raccolta.
type: docs
weight: 118
url: /it/aspose.slides.mathtext/imathblockcollection/clear/
---
## IMathBlockCollection::Clear() metodo

Rimuove tutti gli elementi dalla raccolta.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Clear()=0
```

## Osservazioni

Esempio: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
blockCollection->Clear();
```

## Vedi anche

* Classe [IMathBlockCollection](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)
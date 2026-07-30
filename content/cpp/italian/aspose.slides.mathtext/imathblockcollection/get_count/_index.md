---
title: get_Count()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce il numero di elementi effettivamente contenuti nella raccolta. Solo lettura int32_t.
type: docs
weight: 1
url: /it/aspose.slides.mathtext/imathblockcollection/get_count/
---
## IMathBlockCollection::get_Count() metodo


Restituisce il numero di elementi effettivamente contenuti nella raccolta. Solo lettura **int32_t**.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::get_Count()=0
```

## Osservazioni


Esempio: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
int32_t blocksCount = blockCollection->get_Count();
```

## Vedi anche

* Classe [IMathBlockCollection](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)
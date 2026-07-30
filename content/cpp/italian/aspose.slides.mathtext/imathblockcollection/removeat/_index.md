---
title: RemoveAt()
second_title: Riferimento API di Aspose.Slides per C++
description: Rimuove un elemento all'indice specificato della collezione.
type: docs
weight: 53
url: /it/aspose.slides.mathtext/imathblockcollection/removeat/
---
## IMathBlockCollection::RemoveAt(int32_t) metodo


Rimuove un elemento all'indice specificato della collezione.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::RemoveAt(int32_t index)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | L'indice basato su zero dell'elemento da rimuovere. |
## Osservazioni



Esempio: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
blockCollection->RemoveAt(0);
```

## Vedi anche

* Classe [IMathBlockCollection](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)
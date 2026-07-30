---
title: Add()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge IMathBlock alla fine della collezione.
type: docs
weight: 14
url: /it/aspose.slides.mathtext/imathblockcollection/add/
---
## IMathBlockCollection::Add(System::SharedPtr\<IMathBlock\>) metodo

Aggiunge [IMathBlock](../../imathblock/) alla fine della collezione.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Add(System::SharedPtr<IMathBlock> item)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Un blocco matematico che verrà aggiunto alla fine della collezione |

## Osservazioni



Esempio: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBlock](../../imathblock/)
* Classe [IMathBlockCollection](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
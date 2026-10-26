---
title: Add()
second_title: Riferimento API Aspose.Slides per C++
description: Aggiunge un Paragraph alla fine della collezione.
type: docs
weight: 27
url: /it/aspose.slides/iparagraphcollection/add/
---
## IParagraphCollection::Add(System::SharedPtr\<IParagraph\>) metodo

Aggiunge un [Paragraph](../../paragraph/) alla fine della collezione.

```cpp
virtual void Aspose::Slides::IParagraphCollection::Add(System::SharedPtr<IParagraph> value)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | Il [Paragraph](../../paragraph/) da aggiungere alla fine della collezione. |

## IParagraphCollection::Add(System::SharedPtr\<IParagraphCollection\>) metodo

Aggiunge un contenuto di [ParagraphCollection](../../paragraphcollection/) alla fine della collezione.

```cpp
virtual int32_t Aspose::Slides::IParagraphCollection::Add(System::SharedPtr<IParagraphCollection> value)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraphCollection](../)\> | Il [ParagraphCollection](../../paragraphcollection/) da aggiungere alla fine della collezione. |

### Valore di ritorno

L'indice al quale [Paragraph](../../paragraph/) è stato aggiunto o -1 se non c'è nulla da aggiungere.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IParagraph](../../iparagraph/)
* Classe [IParagraphCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
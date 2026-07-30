---
title: Add()
second_title: Riferimento API Aspose.Slides per C++
description: Aggiunge un Paragrafo alla fine della raccolta.
type: docs
weight: 40
url: /it/aspose.slides/paragraphcollection/add/
---
## ParagraphCollection::Add(System::SharedPtr\<IParagraph\>) metodo


Aggiunge un [Paragraph](../../paragraph/) alla fine della raccolta.

```cpp
void Aspose::Slides::ParagraphCollection::Add(System::SharedPtr<IParagraph> value) override
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | Il [Paragraph](../../paragraph/) da aggiungere alla fine della raccolta. |

## ParagraphCollection::Add(System::SharedPtr\<IParagraphCollection\>) metodo


Aggiunge un contenuto di [ParagraphCollection](../) alla fine della raccolta.

```cpp
int32_t Aspose::Slides::ParagraphCollection::Add(System::SharedPtr<IParagraphCollection> value) override
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraphCollection](../../iparagraphcollection/)\> | Il [ParagraphCollection](../) da aggiungere alla fine della raccolta. |

### Valore di ritorno

L'indice al quale [Paragraph](../../paragraph/) è stato aggiunto o -1 se non c'è nulla da aggiungere.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IParagraph](../../iparagraph/)
* Classe [ParagraphCollection](../)
* Classe [IParagraphCollection](../../iparagraphcollection/)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)
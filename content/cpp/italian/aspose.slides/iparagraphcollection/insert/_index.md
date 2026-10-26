---
title: Insert()
second_title: Riferimento API di Aspose.Slides per C++
description: Inserisce un Paragraph nella collezione all'indice specificato.
type: docs
weight: 40
url: /it/aspose.slides/iparagraphcollection/insert/
---
## IParagraphCollection::Insert(int32_t, System::SharedPtr\<IParagraph\>) metodo


Inserisce un [Paragraph](../../paragraph/) nella collezione all'indice specificato.

```cpp
virtual void Aspose::Slides::IParagraphCollection::Insert(int32_t index, System::SharedPtr<IParagraph> value)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | L'indice a base zero al quale [Paragraph](../../paragraph/) deve essere inserito. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | Il [Paragraph](../../paragraph/) da inserire. |

## IParagraphCollection::Insert(int32_t, System::SharedPtr\<IParagraphCollection\>) metodo


Inserisce un contenuto di [ParagraphCollection](../../paragraphcollection/) nella collezione all'indice specificato.

```cpp
virtual void Aspose::Slides::IParagraphCollection::Insert(int32_t index, System::SharedPtr<IParagraphCollection> value)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | L'indice a base zero al quale i paragrafi devono essere inseriti. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraphCollection](../)\> | I paragrafi da inserire. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IParagraph](../../iparagraph/)
* Classe [IParagraphCollection](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)
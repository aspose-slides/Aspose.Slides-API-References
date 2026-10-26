---
title: Insert()
second_title: Référence de l'API Aspose.Slides pour C++
description: Insère un Paragraph dans la collection à l'index spécifié.
type: docs
weight: 40
url: /fr/aspose.slides/iparagraphcollection/insert/
---
## IParagraphCollection::Insert(int32_t, System::SharedPtr\<IParagraph\>) méthode

Insère un [Paragraph](../../paragraph/) dans la collection à l'indice spécifié.

```cpp
virtual void Aspose::Slides::IParagraphCollection::Insert(int32_t index, System::SharedPtr<IParagraph> value)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which [Paragraph](../../paragraph/) should be inserted. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | The [Paragraph](../../paragraph/) to insert. |

## IParagraphCollection::Insert(int32_t, System::SharedPtr\<IParagraphCollection\>) méthode

Insère le contenu de [ParagraphCollection](../../paragraphcollection/) dans la collection à l'indice spécifié.

```cpp
virtual void Aspose::Slides::IParagraphCollection::Insert(int32_t index, System::SharedPtr<IParagraphCollection> value)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which paragraphs should be inserted. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraphCollection](../)\> | The paragraphs to insert. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IParagraph](../../iparagraph/)
* Classe [IParagraphCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)
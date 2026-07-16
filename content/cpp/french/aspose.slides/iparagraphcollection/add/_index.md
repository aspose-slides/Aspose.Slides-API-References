---
title: Add()
second_title: Référence API Aspose.Slides pour C++
description: Ajoute un Paragraph à la fin de la collection.
type: docs
weight: 27
url: /fr/aspose.slides/iparagraphcollection/add/
---
## IParagraphCollection::Add(System::SharedPtr\<IParagraph\>) méthode


Ajoute un [Paragraph](../../paragraph/) à la fin de la collection.

```cpp
virtual void Aspose::Slides::IParagraphCollection::Add(System::SharedPtr<IParagraph> value)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | Le [Paragraph](../../paragraph/) à ajouter à la fin de la collection. |

## IParagraphCollection::Add(System::SharedPtr\<IParagraphCollection\>) méthode


Ajoute un contenu de [ParagraphCollection](../../paragraphcollection/) à la fin de la collection.

```cpp
virtual int32_t Aspose::Slides::IParagraphCollection::Add(System::SharedPtr<IParagraphCollection> value)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraphCollection](../)\> | Le [ParagraphCollection](../../paragraphcollection/) à ajouter à la fin de la collection. |

### Valeur de retour

L'index auquel le [Paragraph](../../paragraph/) a été ajouté ou -1 s'il n'y a rien à ajouter.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IParagraph](../../iparagraph/)
* Classe [IParagraphCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)
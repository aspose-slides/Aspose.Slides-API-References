---
title: Reorder()
second_title: Référence de l'API Aspose.Slides pour C++
description: Déplace la forme spécifiée vers une nouvelle position dans la collection de formes.
type: docs
weight: 300
url: /fr/aspose.slides/ishapecollection/reorder/
---
## IShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) méthode


Déplace la forme spécifiée vers une nouvelle position dans la collection de formes.

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L’indice cible basé sur zéro où la forme sera placée. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Le [IShape](../../ishape/) à déplacer dans la collection. |

## IShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) méthode


Déplace les formes spécifiées dans la collection de formes, en les plaçant à partir de l’indice donné.

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L’indice cible basé sur zéro où la première forme spécifiée sera placée ; les formes suivantes suivent dans l’ordre fourni. |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | Une ou plusieurs instances de [IShape](../../ishape/) à déplacer dans la collection. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [IShape](../../ishape/)
* Classe [IShapeCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)
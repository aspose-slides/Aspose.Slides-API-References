---
title: Reorder()
second_title: Référence de l'API Aspose.Slides pour C++
description: Déplace la forme spécifiée vers une nouvelle position dans la collection de formes.
type: docs
weight: 339
url: /fr/aspose.slides/shapecollection/reorder/
---
## ShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) méthode

Déplace la forme spécifiée vers une nouvelle position dans la collection de formes.

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L'indice cible basé sur zéro où la forme sera placée. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Le [IShape](../../ishape/) à déplacer dans la collection. |

## ShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) méthode

Déplace les formes spécifiées dans la collection de formes, en les plaçant à partir de l'index donné.

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L'indice cible basé sur zéro où la première forme spécifiée sera placée ; les formes suivantes suivent dans l'ordre fourni. |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | Une ou plusieurs instances de [IShape](../../ishape/) à déplacer dans la collection. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IShape](../../ishape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
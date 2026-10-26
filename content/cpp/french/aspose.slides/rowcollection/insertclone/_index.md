---
title: InsertClone()
second_title: Référence API Aspose.Slides pour C++
description: Crée une copie de la ligne modèle spécifiée et l'insère à la position indiquée dans un tableau.
type: docs
weight: 66
url: /fr/aspose.slides/rowcollection/insertclone/
---
## RowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) method


Crée une copie de la ligne modèle spécifiée et l'insère à la position indiquée dans un tableau.

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Index d'une nouvelle ligne. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) qui est utilisé comme modèle. |
| withAttachedRows | **bool** | True pour copier également toutes les lignes attachées à la ligne modèle. |

### Return Value

Lignes insérées.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IRow](../../irow/)
* Classe [RowCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)
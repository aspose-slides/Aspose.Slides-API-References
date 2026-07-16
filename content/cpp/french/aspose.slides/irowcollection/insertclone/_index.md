---
title: InsertClone()
second_title: Référence API Aspose.Slides pour C++
description: Crée une copie de la ligne modèle spécifiée et l'insère à la position indiquée dans un tableau.
type: docs
weight: 27
url: /fr/aspose.slides/irowcollection/insertclone/
---
## IRowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) method

Crée une copie de la ligne modèle spécifiée et l'insère à la position spécifiée dans un tableau.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Index d'une nouvelle ligne. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) qui est utilisé comme modèle. |
| withAttachedRows | **bool** | True pour copier également toutes les lignes attachées à la ligne modèle. |

### Valeur de retour

Lignes insérées.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IRow](../../irow/)
* Classe [IRowCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)
---
title: InsertClone()
second_title: Référence API Aspose.Slides pour C++
description: Crée une copie de la colonne modèle spécifiée et l'insère à la position indiquée dans un tableau.
type: docs
weight: 66
url: /fr/aspose.slides/columncollection/insertclone/
---
## ColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) method

Crée une copie de la colonne modèle spécifiée et l'insère à la position indiquée dans un tableau.

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Indice de la nouvelle colonne. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) qui est utilisé comme modèle. |
| withAttachedColumns | **bool** | Vrai pour copier également toutes les colonnes attachées à la colonne modèle. |

### Valeur de retour

Colonnes insérées.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IColumn](../../icolumn/)
* Classe [ColumnCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)
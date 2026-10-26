---
title: AddClone()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée une copie de la ligne modèle spécifiée et l'insère au bas d'un tableau.
type: docs
weight: 53
url: /fr/aspose.slides/columncollection/addclone/
---
## ColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) method


Crée une copie de la ligne modèle spécifiée et l'insère au bas d'un tableau.

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) qui est utilisé comme modèle. |
| withAttachedColumns | **bool** | True pour copier également toutes les colonnes attachées à la ligne modèle. |

### Valeur de retour

Added columns.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IColumn](../../icolumn/)
* Class [ColumnCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
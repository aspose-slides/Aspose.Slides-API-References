---
title: AddClone()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée une copie de la ligne modèle spécifiée et l'insère en bas d'une table.
type: docs
weight: 14
url: /fr/aspose.slides/icolumncollection/addclone/
---
## IColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) method

Crée une copie de la ligne modèle spécifiée et l'insère en bas d'une table.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) qui est utilisé comme modèle. |
| withAttachedColumns | **bool** | Vrai pour copier également toutes les colonnes attachées à la ligne modèle. |

### Valeur retournée

Colonnes ajoutées.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IColumn](../../icolumn/)
* Classe [IColumnCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)
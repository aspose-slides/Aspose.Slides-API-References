---
title: InsertClone()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée une copie de la colonne modèle spécifiée et l'insère à la position indiquée dans un tableau.
type: docs
weight: 27
url: /fr/aspose.slides/icolumncollection/insertclone/
---
## IColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) méthode

Crée une copie de la colonne modèle spécifiée et l'insère à la position indiquée dans un tableau.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Indice d'une nouvelle colonne. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) qui est utilisé comme modèle. |
| withAttachedColumns | **bool** | Vrai pour copier également toutes les colonnes attachées à la colonne modèle. |

### Valeur de retour

Colonnes insérées.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IColumn](../../icolumn/)
* Classe [IColumnCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)
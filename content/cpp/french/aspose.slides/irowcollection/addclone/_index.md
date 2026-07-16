---
title: AddClone()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée une copie de la ligne modèle spécifiée et l'insère au bas d'un tableau.
type: docs
weight: 14
url: /fr/aspose.slides/irowcollection/addclone/
---
## IRowCollection::AddClone(System::SharedPtr\<IRow\>, bool) méthode

Crée une copie de la ligne modèle spécifiée et l'insère au bas d'un tableau.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) qui est utilisé comme modèle. |
| withAttachedRows | **bool** | True pour copier également toutes les lignes attachées à la ligne modèle. |

### Valeur de retour

Lignes ajoutées.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IRow](../../irow/)
* Classe [IRowCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)
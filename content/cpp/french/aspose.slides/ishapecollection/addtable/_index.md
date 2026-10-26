---
title: AddTable()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée une nouvelle table et l'ajoute à la fin de la collection de formes.
type: docs
weight: 430
url: /fr/aspose.slides/ishapecollection/addtable/
---
## IShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) method


Crée une nouvelle table et l'ajoute à la fin de la collection de formes.

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| x | **float** | La coordonnée x de la table, en points. |
| y | **float** | La coordonnée y de la table, en points. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Un tableau de doubles représentant les largeurs des colonnes de la table\\u2019s, en points. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Un tableau de doubles représentant les hauteurs des lignes de la table\\u2019s, en points. |

### Valeur de retour

The newly created [ITable](../../itable/).

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ITable](../../itable/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
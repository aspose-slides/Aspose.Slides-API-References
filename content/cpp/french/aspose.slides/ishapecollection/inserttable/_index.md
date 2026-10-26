---
title: InsertTable()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un nouveau tableau et l'insère dans la collection de formes à l'indice spécifié.
type: docs
weight: 443
url: /fr/aspose.slides/ishapecollection/inserttable/
---
## IShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) méthode

Crée un nouveau table et l’insère dans la collection de formes à l’indice spécifié.

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L’indice basé sur zéro où insérer le table. |
| x | **float** | La coordonnée x du table, en points. |
| y | **float** | La coordonnée y du table, en points. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Un tableau de doubles représentant les largeurs des colonnes du table, en points. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Un tableau de doubles représentant les hauteurs des lignes du table, en points. |

### Valeur de retour

Le [ITable](../../itable/) nouvellement créé.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ITable](../../itable/)
* Classe [IShapeCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)
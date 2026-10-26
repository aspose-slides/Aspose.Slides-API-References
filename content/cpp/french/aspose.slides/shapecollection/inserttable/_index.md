---
title: InsertTable()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un nouveau tableau et l'insère dans la collection de formes à l'index spécifié.
type: docs
weight: 482
url: /fr/aspose.slides/shapecollection/inserttable/
---
## ShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) méthode

Crée un nouveau tableau et l'insère dans la collection de formes à l'index spécifié.

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L'index à base zéro où insérer le tableau. |
| x | **float** | La coordonnée x du tableau, en points. |
| y | **float** | La coordonnée y du tableau, en points. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Un tableau de doubles représentant les largeurs des colonnes du tableau, en points. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Un tableau de doubles représentant les hauteurs des lignes du tableau, en points. |

### Valeur de retour

Le [ITable](../../itable/) nouvellement créé.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ITable](../../itable/)
* Classe [ShapeCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)
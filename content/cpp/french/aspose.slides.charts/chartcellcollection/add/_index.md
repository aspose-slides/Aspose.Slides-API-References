---
title: Add()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute une nouvelle cellule à la collection.
type: docs
weight: 53
url: /fr/aspose.slides.charts/chartcellcollection/add/
---
## ChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) méthode

Ajoute une nouvelle cellule à la collection.

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<IChartDataCell> cell) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| cell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | New cell to add. |

## ChartCellCollection::Add(System::SharedPtr\<System::Object\>) méthode

Crée [ChartDataCell](../../chartdatacell/) à partir de la valeur spécifiée et l’ajoute à la collection.

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<System::Object> value) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | The value. |
## Remarques

Cette méthode ajoute une feuille de calcul nommée AUTO_DATA et y ajoute toutes les valeurs. Si vous utilisez [ChartDataWorkbook](../../chartdataworkbook/) pour ajouter ou modifier les valeurs [Cell](../../../aspose.slides/cell/), assurez-vous de ne pas utiliser cette feuille de calcul. Le nombre maximal de valeurs ajoutées avec cette méthode ne doit pas dépasser 16711680

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartDataCell](../../ichartdatacell/)
* Classe [ChartCellCollection](../)
* Classe [Object](../../../system/object/)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)
---
title: Add()
second_title: Référence API Aspose.Slides pour C++
description: Ajoute une nouvelle cellule à la collection.
type: docs
weight: 53
url: /fr/aspose.slides.charts/ichartcellcollection/add/
---
## IChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) méthode


Ajoute une nouvelle cellule à la collection.

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Nouvelle cellule à ajouter. |

## IChartCellCollection::Add(System::SharedPtr\<System::Object\>) méthode


Crée [IChartDataCell](../../ichartdatacell/) à partir de la valeur spécifiée et l'ajoute à la collection.

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<System::Object> value)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | La valeur. |
## Remarques



Cette méthode ajoute une feuille de calcul nommée AUTO_DATA et y ajoute toutes les valeurs. Si vous utilisez [IChartDataWorkbook](../../ichartdataworkbook/) pour ajouter ou modifier les valeurs [Cell](../../../aspose.slides/cell/), assurez-vous de ne pas utiliser cette feuille de calcul. Le nombre maximal de valeurs ajoutées avec cette méthode ne doit pas dépasser 16711680



## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartDataCell](../../ichartdatacell/)
* Classe [IChartCellCollection](../)
* Classe [Object](../../../system/object/)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)
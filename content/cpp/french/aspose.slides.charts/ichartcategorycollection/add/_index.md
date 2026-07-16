---
title: Add()
second_title: Référence API Aspose.Slides pour C++
description: Si la catégorie existe dans la collection, la retourner. Sinon, crée une nouvelle catégorie de graphique à partir de IChartDataCell et l'ajoute à la collection.
type: docs
weight: 53
url: /fr/aspose.slides.charts/ichartcategorycollection/add/
---
## IChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) méthode


Si la catégorie existe dans la collection, la retourner. Sinon, crée une nouvelle catégorie de graphique à partir de [IChartDataCell](../../ichartdatacell/) et l'ajoute à la collection.

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) utilisé pour créer une catégorie de graphique. |

### Valeur de retour

Catégorie ajoutée ou existante.



## IChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) méthode


Crée un nouveau [IChartCategory](../../ichartcategory/) à partir de la valeur et l'ajoute à la collection.

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<System::Object> value)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | La valeur. |

### Valeur de retour

Ajouté [IChartCategory](../../ichartcategory/).
## Remarques



Cette méthode ajoute une feuille de calcul nommée AUTO_DATA et y ajoute toutes les valeurs. Si vous utilisez [IChartDataWorkbook](../../ichartdataworkbook/) pour ajouter ou modifier des valeurs de cellule, assurez-vous de ne pas utiliser cette feuille de calcul. Le nombre maximal de valeurs ajoutées avec cette méthode ne doit pas dépasser 16711680



## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartCategory](../../ichartcategory/)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [IChartCategoryCollection](../)
* Class [Object](../../../system/object/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
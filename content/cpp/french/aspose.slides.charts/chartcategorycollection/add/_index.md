---
title: Add()
second_title: Référence API Aspose.Slides pour C++
description: Si la catégorie existe dans la collection, la renvoie. Sinon, crée une nouvelle catégorie de diagramme à partir de IChartDataCell et l’ajoute à la collection.
type: docs
weight: 92
url: /fr/aspose.slides.charts/chartcategorycollection/add/
---
## ChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) méthode


Si la catégorie existe dans la collection, la renvoie. Sinon, crée une nouvelle catégorie de diagramme à partir de [IChartDataCell](../../ichartdatacell/) et l’ajoute à la collection.

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell) override
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) utilisé pour créer la catégorie de diagramme. |

### Valeur retournée

Catégorie ajoutée ou existante.



## ChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) méthode


Crée un nouveau [ChartCategory](../../chartcategory/) à partir de la valeur et l’ajoute à la collection.

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<System::Object> value) override
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | La valeur. |

### Valeur retournée

Ajouté [IChartCategory](../../ichartcategory/).
## Remarques



Cette méthode ajoute une feuille de calcul nommée AUTO_DATA et y ajoute toutes les valeurs. Si vous utilisez [ChartDataWorkbook](../../chartdataworkbook/) pour ajouter ou modifier les valeurs des cellules, assurez vous de ne pas utiliser cette feuille de calcul. Le nombre maximum de valeurs ajoutées avec cette méthode ne doit pas dépasser 16711680



## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartCategory](../../ichartcategory/)
* Classe [IChartDataCell](../../ichartdatacell/)
* Classe [ChartCategoryCollection](../)
* Classe [Object](../../../system/object/)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)
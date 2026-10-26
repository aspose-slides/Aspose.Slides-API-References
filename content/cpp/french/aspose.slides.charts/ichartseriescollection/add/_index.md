---
title: Add()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée une nouvelle série de graphique et l'ajoute à la collection.
type: docs
weight: 14
url: /fr/aspose.slides.charts/ichartseriescollection/add/
---
## IChartSeriesCollection::Add(ChartType) méthode


Crée une nouvelle série de graphique et l'ajoute à la collection.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(ChartType type)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | Type de série |

### Valeur de retour

Nouvelle série de graphique.

## IChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) méthode


Crée une nouvelle série de graphique à partir de [IChartDataCell](../../ichartdatacell/) et l'ajoute à la collection.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) qui contient le nom de la série. |
| type | [ChartType](../../charttype/) | Type définit le type de série |

### Valeur de retour

Série de graphique ajoutée ou série déjà présente dans la collection.

## Remarques


Si la série de graphique est créée à partir de la même cellule déjà présente dans la collection, alors la méthode n'ajoute rien et renvoie son index.



## IChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) méthode


Crée une nouvelle série de graphique à partir de [IChartCellCollection](../../ichartcellcollection/) et l'ajoute à la collection.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | Cellules contenant le nom de la série. |
| type | [ChartType](../../charttype/) | Type définit le type de série |

### Valeur de retour

Série de graphique ajoutée ou série déjà présente dans la collection.

## Remarques


Si la série de graphique est créée à partir de la même cellule déjà présente dans la collection, alors la méthode n'ajoute rien et renvoie son index.



## IChartSeriesCollection::Add(System::String, ChartType) méthode


Crée une nouvelle série de graphique à partir d'une valeur et l'ajoute à la collection.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::String name, ChartType type)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | Nom de la série. |
| type | [ChartType](../../charttype/) | Type définit le type de série |

### Valeur de retour

Série de graphique ajoutée.



## Voir aussi

* Enum [ChartType](../../charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartSeries](../../ichartseries/)
* Class [IChartSeriesCollection](../)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [IChartCellCollection](../../ichartcellcollection/)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
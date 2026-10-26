---
title: Add()
second_title: Référence d'API Aspose.Slides pour C++
description: Crée de nouvelles séries de graphique et les ajoute à la collection.
type: docs
weight: 53
url: /fr/aspose.slides.charts/chartseriescollection/add/
---
## ChartSeriesCollection::Add(ChartType) méthode


Creates new chart series and adds it to the collection.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(ChartType type) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | Type de série |

### Valeur de retour

New chart series.

## ChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) méthode


Creates new chart series from [ChartDataCell](../../chartdatacell/) and adds it to the collection.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) qui contient le nom de la série. |
| type | [ChartType](../../charttype/) | Type défini du type de la série |

### Valeur de retour

Added chart series or series that already is in collection.

## Remarques


If chart series careted from same cell already in collection then method adds nothing and returns it's index.



## ChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) méthode


Creates new chart series from [ChartCellCollection](../../chartcellcollection/) and adds it to the collection.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | Cells which contain series name. |
| type | [ChartType](../../charttype/) | Type set type of series |

### Valeur de retour

Added chart series or series that already is in collection.

## Remarques


If chart series careted from same cell already in collection then method adds nothing and returns it's index.



## ChartSeriesCollection::Add(System::String, ChartType) méthode


Creates new chart series from value and adds it to the collection.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::String name, ChartType type) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | Series name. |
| type | [ChartType](../../charttype/) | Type set type of series |

### Valeur de retour

Added chart series.



## Voir aussi

* Enum [ChartType](../../charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartSeries](../../ichartseries/)
* Class [ChartSeriesCollection](../)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [IChartCellCollection](../../ichartcellcollection/)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
---
title: Add()
second_title: Aspose.Slides for C++ API Reference
description: Creates new chart series and adds it to the collection.
type: docs
weight: 14
url: /aspose.slides.charts/ichartseriescollection/add/
---
## IChartSeriesCollection::Add(ChartType) method


Creates new chart series and adds it to the collection.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(ChartType type)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | Type of series |

### Return Value

New chart series.

## IChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) method


Creates new chart series from [IChartDataCell](../../ichartdatacell/) and adds it to the collection.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) which contain series name. |
| type | [ChartType](../../charttype/) | Type set type of series |

### Return Value

Added chart series or series that already is in collection.
## Remarks


If chart series careted from same cell already in collection then method adds nothing and returns it's index.



## IChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) method


Creates new chart series from [IChartCellCollection](../../ichartcellcollection/) and adds it to the collection.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | Cells which contain series name. |
| type | [ChartType](../../charttype/) | Type set type of series |

### Return Value

Added chart series or series that already is in collection.
## Remarks


If chart series careted from same cell already in collection then method adds nothing and returns it's index.



## IChartSeriesCollection::Add(System::String, ChartType) method


Creates new chart series from value and adds it to the collection.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::String name, ChartType type)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | Series name. |
| type | [ChartType](../../charttype/) | Type set type of series |

### Return Value

Added chart series.



## See Also

* Enum [ChartType](../../charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartSeries](../../ichartseries/)
* Class [IChartSeriesCollection](../)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [IChartCellCollection](../../ichartcellcollection/)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
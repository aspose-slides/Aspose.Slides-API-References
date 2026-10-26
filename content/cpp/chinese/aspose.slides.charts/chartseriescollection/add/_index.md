---
title: Add()
second_title: Aspose.Slides for C++ API 参考
description: 创建新的图表系列并将其添加到集合中。
type: docs
weight: 53
url: /zh/aspose.slides.charts/chartseriescollection/add/
---
## ChartSeriesCollection::Add(ChartType) 方法


创建新的图表系列并将其添加到集合中。

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(ChartType type) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | 系列的类型 |

### 返回值

新的图表系列。

## ChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) 方法


从 [ChartDataCell](../../chartdatacell/) 创建新的图表系列并将其添加到集合中。

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/)，其中包含系列名称。 |
| type | [ChartType](../../charttype/) | 系列的类型设置 |

### 返回值

已添加的图表系列，或已经在集合中的系列。

## 备注


如果从已经在集合中的相同单元格创建图表系列，则方法不添加任何内容并返回它的索引。



## ChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) 方法


从 [ChartCellCollection](../../chartcellcollection/) 创建新的图表系列并将其添加到集合中。

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | 包含系列名称的单元格。 |
| type | [ChartType](../../charttype/) | 系列的类型设置 |

### 返回值

已添加的图表系列，或已经在集合中的系列。

## 备注


如果从已经在集合中的相同单元格创建图表系列，则方法不添加任何内容并返回它的索引。



## ChartSeriesCollection::Add(System::String, ChartType) 方法


从值创建新的图表系列并将其添加到集合中。

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::String name, ChartType type) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | 系列名称。 |
| type | [ChartType](../../charttype/) | 系列的类型设置 |

### 返回值

已添加的图表系列。

## 另见

* Enum [ChartType](../../charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartSeries](../../ichartseries/)
* Class [ChartSeriesCollection](../)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [IChartCellCollection](../../ichartcellcollection/)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
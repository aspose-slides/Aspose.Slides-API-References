---
title: Add()
second_title: Aspose.Slides for C++ API 參考
description: 建立新的圖表系列並將其加入集合。
type: docs
weight: 14
url: /zh-hant/aspose.slides.charts/ichartseriescollection/add/
---
## IChartSeriesCollection::Add(ChartType) 方法

建立新的圖表系列並將其加入集合。

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(ChartType type)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | 系列的類型 |

### 回傳值

新的圖表系列。

## IChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) 方法

從 [IChartDataCell](../../ichartdatacell/) 建立新的圖表系列並將其加入集合。

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) 包含系列名稱的 |
| type | [ChartType](../../charttype/) | 設定系列類型的型別 |

### 回傳值

已加入的圖表系列，或已在集合中的系列。

## 備註

如果圖表系列是從已在集合中的相同儲存格建立，則此方法不會新增任何內容，並傳回其索引。

## IChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) 方法

從 [IChartCellCollection](../../ichartcellcollection/) 建立新的圖表系列並將其加入集合。

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | 包含系列名稱的儲存格。 |
| type | [ChartType](../../charttype/) | 設定系列類型的型別 |

### 回傳值

已加入的圖表系列，或已在集合中的系列。

## 備註

如果圖表系列是從已在集合中的相同儲存格建立，則此方法不會新增任何內容，並傳回其索引。

## IChartSeriesCollection::Add(System::String, ChartType) 方法

從值建立新的圖表系列並將其加入集合。

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::String name, ChartType type)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | 系列名稱。 |
| type | [ChartType](../../charttype/) | 設定系列類型的型別 |

### 回傳值

已加入的圖表系列。

## 另請參閱

* Enum [ChartType](../../charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IChartSeries](../../ichartseries/)
* 類別 [IChartSeriesCollection](../)
* 類別 [IChartDataCell](../../ichartdatacell/)
* 類別 [IChartCellCollection](../../ichartcellcollection/)
* 類別 [String](../../../system/string/)
* 命名空間 [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
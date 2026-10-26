---
title: Add()
second_title: Aspose.Slides for C++ API 參考
description: 建立新的圖表系列並將其加入集合。
type: docs
weight: 53
url: /zh-hant/aspose.slides.charts/chartseriescollection/add/
---
## ChartSeriesCollection::Add(ChartType) 方法

建立新的圖表系列並將其加入集合。

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(ChartType type) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | 系列的類型 |

### 傳回值

新的圖表系列。

## ChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) 方法

從 [ChartDataCell](../../chartdatacell/) 建立新的圖表系列並將其加入集合。

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) 包含系列名稱。 |
| type | [ChartType](../../charttype/) | 設定系列類型 |

### 傳回值

已加入的圖表系列，或已在集合中的系列。

## 備註

如果圖表系列是從已在集合中的同一儲存格建立，則方法不會添加任何內容，並傳回其索引。

## ChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) 方法

從 [ChartCellCollection](../../chartcellcollection/) 建立新的圖表系列並將其加入集合。

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | 包含系列名稱的儲存格。 |
| type | [ChartType](../../charttype/) | 設定系列類型 |

### 傳回值

已加入的圖表系列，或已在集合中的系列。

## 備註

如果圖表系列是從已在集合中的同一儲存格建立，則方法不會添加任何內容，並傳回其索引。

## ChartSeriesCollection::Add(System::String, ChartType) 方法

從值建立新的圖表系列並將其加入集合。

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::String name, ChartType type) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | 系列名稱。 |
| type | [ChartType](../../charttype/) | 設定系列類型 |

### 傳回值

已加入的圖表系列。

## 另請參閱

* 列舉 [ChartType](../../charttype/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IChartSeries](../../ichartseries/)
* 類別 [ChartSeriesCollection](../)
* 類別 [IChartDataCell](../../ichartdatacell/)
* 類別 [IChartCellCollection](../../ichartcellcollection/)
* 類別 [String](../../../system/string/)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)
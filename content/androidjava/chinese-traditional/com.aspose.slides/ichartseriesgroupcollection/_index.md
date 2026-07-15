---
title: IChartSeriesGroupCollection
second_title: Aspose.Slides for Android via Java API 參考
description: 表示可組合系列群組的集合。
type: docs
url: /zh-hant/com.aspose.slides/ichartseriesgroupcollection/
---
**所有已實作的介面：**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesGroupCollection extends IGenericCollection<IChartSeriesGroup>
```

代表可組合系列群組的集合。

--------------------

1) 每個系列群組包含具有可組合類型的系列。使用 CombinableSeriesTypesGroup enum 定義與描述可組合系列類型群組。另外，每個系列群組中的系列會繪製於主軸或次軸（同一群組不會同時在兩者上）。因此，系列分組的原則是依上述類型群組以及主/次軸繪製類型進行分組。2) 系列群組包含一些對群組中每個系列皆通用的系列屬性（「系列群組屬性」）。ChartSeriesGroup 類別中的「系列群組屬性」為可讀寫。每個「系列群組屬性」在 ChartSeries 類別中可有只讀投影。
## Methods

| Method | Description |
| --- | --- |
| [get_Item(IChartSeries ofSeries)](#get-Item-com.aspose.slides.IChartSeries-) | 依系列取得系列群組。 |
| [get_Item(int index)](#get-Item-int-) | 依索引取得系列群組。 |
### get_Item(IChartSeries ofSeries) {#get-Item-com.aspose.slides.IChartSeries-}
```
public abstract IChartSeriesGroup get_Item(IChartSeries ofSeries)
```


依系列取得系列群組。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ofSeries | [IChartSeries](../../com.aspose.slides/ichartseries) |  |

**Returns:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeriesGroup get_Item(int index)
```


依索引取得系列群組。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
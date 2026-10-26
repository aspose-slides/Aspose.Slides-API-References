---
title: IChartSeriesGroupCollection
second_title: Aspose.Slides for Java API 參考文件
description: 表示可組合系列群組的集合。
type: docs
url: /zh-hant/com.aspose.slides/ichartseriesgroupcollection/
---
**所有已實作的介面：**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesGroupCollection extends IGenericCollection<IChartSeriesGroup>
```

表示可組合系列群組的集合。

--------------------

1) 每個系列群組包含具有可組合類型的系列。可組合系列類型的群組以 CombinableSeriesTypesGroup 列舉定義與說明。此外，每個系列群組包含的系列會繪製在主座標軸或次座標軸上（不會同時在同一群組中出現兩種情況）。因此，系列分組的原則是依上述類型群組以及主/次座標繪製類型進行分組。 2) 系列群組包含一些對該群組中每個系列都共通的系列屬性（「Series group properties」）。ChartSeriesGroup 類別中的「Series group properties」為可讀寫。每個「Series group properties」在 ChartSeries 類別中可以有一個唯讀的投影。

## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(IChartSeries ofSeries)](#get-Item-com.aspose.slides.IChartSeries-) | 取得系列所屬的系列群組。 |
| [get_Item(int index)](#get-Item-int-) | 依索引取得系列群組。 |
### get_Item(IChartSeries ofSeries) {#get-Item-com.aspose.slides.IChartSeries-}
```
public abstract IChartSeriesGroup get_Item(IChartSeries ofSeries)
```

取得系列所屬的系列群組。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| ofSeries | [IChartSeries](../../com.aspose.slides/ichartseries) |  |

**傳回值：**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeriesGroup get_Item(int index)
```

依索引取得系列群組。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回值：**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
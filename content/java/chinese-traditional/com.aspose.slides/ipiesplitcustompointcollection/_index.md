---
title: IPieSplitCustomPointCollection
second_title: Aspose.Slides for Java API 參考
description: 表示一個集合，其中的點將在條形-餅圖或餅形-餅圖的第二個餅或條形上繪製，並使用自訂分割。
type: docs
url: /zh-hant/com.aspose.slides/ipiesplitcustompointcollection/
---
**所有已實作的介面：**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IPieSplitCustomPointCollection extends System.Collections.Generic.IGenericCollection<IChartDataPoint>
```

表示一個集合，其中的點將在條形-餅圖或餅形-餅圖的第二個餅或條形上繪製，並使用自訂分割。
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 根據索引返回圖表資料點。 |
| [add(int dataPointIndex)](#add-int-) | 根據其在父系列點集合中的索引新增資料點。 |
| [remove(int dataPointIndex)](#remove-int-) | 根據其在父系列點集合中的索引從集合中移除項目。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```


根據索引返回圖表資料點。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 資料點的索引。 |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 圖表資料點。
### add(int dataPointIndex) {#add-int-}
```
public abstract void add(int dataPointIndex)
```


根據其在父系列點集合中的索引新增資料點。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| dataPointIndex | int | 資料點在父系列點集合中的索引。 |

### remove(int dataPointIndex) {#remove-int-}
```
public abstract void remove(int dataPointIndex)
```


根據其在父系列點集合中的索引從集合中移除項目。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| dataPointIndex | int | 資料點在父系列點集合中的索引。 |
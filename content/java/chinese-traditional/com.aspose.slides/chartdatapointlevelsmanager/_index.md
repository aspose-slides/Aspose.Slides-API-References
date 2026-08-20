---
title: ChartDataPointLevelsManager
second_title: Aspose.Slides Java API 參考
description: 資料點層級的容器。
type: docs
url: /zh-hant/com.aspose.slides/chartdatapointlevelsmanager/
---
**繼承:**  
java.lang.Object, com.aspose.slides.DomObject

**所有實作的介面:**  
[com.aspose.slides.IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)  
```
public class ChartDataPointLevelsManager extends DomObject<ChartDataPoint> implements IChartDataPointLevelsManager
```

容器，用於資料點層級。適用於 Treeamp 與 Sunburst 系列。資料點層級的索引從零開始。

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | 返回 IChartDataPointLevel 物件以取得指定層級。 |
| [getCount()](#getCount--) | 返回資料點層級的計數。 |
### get_Item(int level) {#get-Item-int-}
```
public final IChartDataPointLevel get_Item(int level)
```

返回 IChartDataPointLevel 物件以取得指定層級。

**參數:**  
| Parameter | Type | Description |
| --- | --- | --- |
| level | int |  |

**返回:**  
[IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
### getCount() {#getCount--}
```
public final int getCount()
```

返回資料點層級的計數。

**返回:**  
int
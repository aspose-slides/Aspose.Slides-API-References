---
title: ChartDataPointLevelsManager
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 資料點層級的容器。
type: docs
url: /zh-hant/com.aspose.slides/chartdatapointlevelsmanager/
---
**繼承：**
java.lang.Object, com.aspose.slides.DomObject

**所有已實作的介面：**
[com.aspose.slides.IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
```
public class ChartDataPointLevelsManager extends DomObject<ChartDataPoint> implements IChartDataPointLevelsManager
```

資料點層級的容器。適用於 Treeamp 與 Sunburst 系列。資料點層級的索引從零開始。

## 方法

| Method | Description |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | 傳回為指定層級的 IChartDataPointLevel 物件。 |
| [getCount()](#getCount--) | 傳回資料點層級的計數。 |
### get_Item(int level) {#get-Item-int-}
```
public final IChartDataPointLevel get_Item(int level)
```


傳回為指定層級的 IChartDataPointLevel 物件。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| level | int |  |

**傳回值:**
[IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
### getCount() {#getCount--}
```
public final int getCount()
```


傳回資料點層級的計數。

**傳回值:**
int
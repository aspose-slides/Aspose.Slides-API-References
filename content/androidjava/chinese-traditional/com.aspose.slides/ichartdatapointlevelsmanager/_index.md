---
title: IChartDataPointLevelsManager
second_title: Aspose.Slides for Android via Java API Reference
description: 資料點層級的容器。
type: docs
url: /zh-hant/com.aspose.slides/ichartdatapointlevelsmanager/
---```
public interface IChartDataPointLevelsManager
```

資料點層級的容器。適用於 Treeamp 和 Sunburst 系列。資料點層級索引採用零基制。
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | 傳回為指定層級的 IChartDataPointLevel 物件。 |
| [getCount()](#getCount--) | 傳回資料點層級的計數。 |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataPointLevel get_Item(int level)
```

傳回為指定層級的 IChartDataPointLevel 物件。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| level | int |  |

**傳回值：**
[IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
### getCount() {#getCount--}
```
public abstract int getCount()
```

傳回資料點層級的計數。

**傳回值：**
int
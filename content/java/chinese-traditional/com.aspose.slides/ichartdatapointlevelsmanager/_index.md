---
title: IChartDataPointLevelsManager
second_title: Aspose.Slides for Java API 參考
description: 資料點層級的容器。
type: docs
url: /zh-hant/com.aspose.slides/ichartdatapointlevelsmanager/
---```
public interface IChartDataPointLevelsManager
```

資料點層級的容器。適用於 Treeamp 和 Sunburst 系列。資料點層級的索引從零開始。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | 返回為指定層級的 IChartDataPointLevel 物件。 |
| [getCount()](#getCount--) | 返回資料點層級的計數。 |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataPointLevel get_Item(int level)
```

返回為指定層級的 IChartDataPointLevel 物件。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| level | int |  |

**返回值：**
[IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
### getCount() {#getCount--}
```
public abstract int getCount()
```

返回資料點層級的計數。

**返回值：**
int
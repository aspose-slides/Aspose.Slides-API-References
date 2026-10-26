---
title: IChartDataPointLevelsManager
second_title: Aspose.Slides for Java API Reference
description: 数据点级别的容器。适用于 Treeamp 和 Sunburst 系列。数据点级别的索引为零基。
type: docs
url: /zh/com.aspose.slides/ichartdatapointlevelsmanager/
---```
public interface IChartDataPointLevelsManager
```

数据点级别的容器。适用于 Treeamp 和 Sunburst 系列。数据点级别的索引为零基。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | 返回为指定级别的 IChartDataPointLevel 对象。 |
| [getCount()](#getCount--) | 返回数据点级别的计数。 |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataPointLevel get_Item(int level)
```


返回为指定级别的 IChartDataPointLevel 对象。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| level | int |  |

**返回：**
[IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
### getCount() {#getCount--}
```
public abstract int getCount()
```


返回数据点级别的计数。

**返回：**
int
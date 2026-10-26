---
title: IChartDataPointLevelsManager
second_title: Aspose.Slides for Android via Java API Reference
description: 数据点级别的容器。
type: docs
url: /zh/com.aspose.slides/ichartdatapointlevelsmanager/
---```
public interface IChartDataPointLevelsManager
```

数据点级别的容器。适用于 Treeamp 和 Sunburst 系列。数据点级别索引基于零。

## 方法

| Method | Description |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | 返回为定义的级别的 IChartDataPointLevel 对象。 |
| [getCount()](#getCount--) | 返回数据点级别的计数。 |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataPointLevel get_Item(int level)
```


返回为定义的级别的 IChartDataPointLevel 对象。

**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| level | int |  |

**返回:**
[IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
### getCount() {#getCount--}
```
public abstract int getCount()
```


返回数据点级别的计数。

**返回:**
int
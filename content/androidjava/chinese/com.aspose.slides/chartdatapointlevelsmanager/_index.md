---
title: ChartDataPointLevelsManager
second_title: Aspose.Slides for Android via Java API 参考
description: 数据点级别的容器。
type: docs
url: /zh/com.aspose.slides/chartdatapointlevelsmanager/
---
**继承:**  
java.lang.Object, com.aspose.slides.DomObject

**所有实现的接口:**  
[com.aspose.slides.IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)  
```
public class ChartDataPointLevelsManager extends DomObject<ChartDataPoint> implements IChartDataPointLevelsManager
```

数据点级别的容器。适用于 Treeamp 和 Sunburst 系列。数据点级别的索引从零开始。

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | 返回定义级别的 IChartDataPointLevel 对象。 |
| [getCount()](#getCount--) | 返回数据点级别计数。 |

### get_Item(int level) {#get-Item-int-}
```
public final IChartDataPointLevel get_Item(int level)
```

返回定义级别的 IChartDataPointLevel 对象。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| level | int |  |

**返回：**
[IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)

### getCount() {#getCount--}
```
public final int getCount()
```

返回数据点级别计数。

**返回：**
int
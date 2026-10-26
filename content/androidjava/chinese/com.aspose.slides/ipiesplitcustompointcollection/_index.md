---
title: IPieSplitCustomPointCollection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一个点集合，这些点将在带自定义分割的条形-饼图或饼形-饼图的第二个饼或条形中绘制。
type: docs
url: /zh/com.aspose.slides/ipiesplitcustompointcollection/
---
**所有已实现的接口：**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IPieSplitCustomPointCollection extends System.Collections.Generic.IGenericCollection<IChartDataPoint>
```

表示一个点集合，这些点将在带自定义分割的条形-饼图或饼形-饼图的第二个饼或条形中绘制。

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 按索引返回图表数据点。 |
| [add(int dataPointIndex)](#add-int-) | 按在父序列点集合中的索引添加数据点。 |
| [remove(int dataPointIndex)](#remove-int-) | 按在父序列点集合中的索引从集合中移除项。 |

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

按索引返回图表数据点。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 数据点的索引。 |

**返回值：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 图表数据点。

### add(int dataPointIndex) {#add-int-}
```
public abstract void add(int dataPointIndex)
```

按在父序列点集合中的索引添加数据点。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dataPointIndex | int | 父序列点集合中数据点的索引。 |

### remove(int dataPointIndex) {#remove-int-}
```
public abstract void remove(int dataPointIndex)
```

按在父序列点集合中的索引从集合中移除项。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dataPointIndex | int | 父序列点集合中数据点的索引.. |
---
title: IPieSplitCustomPointCollection
second_title: Aspose.Slides for Java API 参考
description: 表示一个点集合，这些点将在条形-饼图或饼形-条形图的第二个饼形或条形中绘制，并使用自定义分割。
type: docs
url: /zh/com.aspose.slides/ipiesplitcustompointcollection/
---
**所有实现的接口：**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IPieSplitCustomPointCollection extends System.Collections.Generic.IGenericCollection<IChartDataPoint>
```

表示一个点集合，这些点将在条形-饼图或饼形-条形图的第二个饼形或条形中绘制，并使用自定义分割。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 按索引返回图表数据点。 |
| [add(int dataPointIndex)](#add-int-) | 通过其在父系列点集合中的索引添加数据点。 |
| [remove(int dataPointIndex)](#remove-int-) | 通过其在父系列点集合中的索引从集合中移除项。 |
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

通过其在父系列点集合中的索引添加数据点。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dataPointIndex | int | 数据点在父系列点集合中的索引。 |

### remove(int dataPointIndex) {#remove-int-}
```
public abstract void remove(int dataPointIndex)
```

通过其在父系列点集合中的索引从集合中移除项。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dataPointIndex | int | 数据点在父系列点集合中的索引。 |
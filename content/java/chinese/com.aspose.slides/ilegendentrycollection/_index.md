---
title: ILegendEntryCollection
second_title: Aspose.Slides for Java API Reference
description: Represents legends collection.
type: docs
url: /zh/com.aspose.slides/ilegendentrycollection/
---```
public interface ILegendEntryCollection
```

表示图例集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 获取对应于 Chart.ChartData.Series[0].DataPoints[index] 的图例条目属性（当图表类型为以下列表中的一种时：ChartType.BarOfPie、ChartType.ExplodedPie、ChartType.ExplodedPie3D、ChartType.Pie、ChartType.Pie3D、ChartType.PieOfPie）；或对应于其他图表类型的 Chart.ChartData.Series[index]。 |
| [getCount()](#getCount--) | 获取集合中实际包含的元素数量。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILegendEntryProperties get_Item(int index)
```

获取对应于 Chart.ChartData.Series[0].DataPoints[index] 的图例条目属性（当图表类型为以下列表中的一种时：ChartType.BarOfPie、ChartType.ExplodedPie、ChartType.ExplodedPie3D、ChartType.Pie、ChartType.Pie3D、ChartType.PieOfPie）；或对应于其他图表类型的 Chart.ChartData.Series[index]。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回值:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public abstract int getCount()
```

获取集合中实际包含的元素数量。只读 int。

**返回值:**
int
---
title: LegendEntryCollection
second_title: Aspose.Slides 的 Java API 参考
description: 表示图例集合。
type: docs
url: /zh/com.aspose.slides/legendentrycollection/
---
**继承:**
java.lang.Object

**所有实现的接口:**
[com.aspose.slides.ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)
```
public class LegendEntryCollection implements ILegendEntryCollection
```

表示图例集合。

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 获取对应于 Chart.ChartData.Series[0].DataPoints[index] 的图例条目属性（当图表类型为以下列表中的一种时：ChartType.BarOfPie、ChartType.ExplodedPie、ChartType.ExplodedPie3D、ChartType.Pie、ChartType.Pie3D、ChartType.PieOfPie）；或对应于其他图表类型的 Chart.ChartData.Series[index] 的图例条目属性。 |
| [getCount()](#getCount--) | 获取图例条目的数量。 |
### get_Item(int index) {#get-Item-int-}
```
public final ILegendEntryProperties get_Item(int index)
```

获取对应于 Chart.ChartData.Series[0].DataPoints[index] 的图例条目属性（当图表类型为以下列表中的一种时：ChartType.BarOfPie、ChartType.ExplodedPie、ChartType.ExplodedPie3D、ChartType.Pie、ChartType.Pie3D、ChartType.PieOfPie）；或对应于其他图表类型的 Chart.ChartData.Series[index] 的图例条目属性。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回值:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public final int getCount()
```

获取图例条目的数量。只读 int。

**返回值:**
int
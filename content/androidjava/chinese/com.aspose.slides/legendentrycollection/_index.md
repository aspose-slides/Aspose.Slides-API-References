---
title: LegendEntryCollection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示图例集合。
type: docs
url: /zh/com.aspose.slides/legendentrycollection/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)
```
public class LegendEntryCollection implements ILegendEntryCollection
```

表示图例集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 获取对应于 Chart.ChartData.Series[0].DataPoints[index] 的图例条目的属性，适用于以下图表类型：ChartType.BarOfPie、ChartType.ExplodedPie、ChartType.ExplodedPie3D、ChartType.Pie、ChartType.Pie3D、ChartType.PieOfPie；或对于其他图表类型，对应于 Chart.ChartData.Series[index]。 |
| [getCount()](#getCount--) | 获取图例条目的数量。 |
### get_Item(int index) {#get-Item-int-}
```
public final ILegendEntryProperties get_Item(int index)
```


获取对应于 Chart.ChartData.Series[0].DataPoints[index] 的图例条目的属性，适用于以下图表类型：ChartType.BarOfPie、ChartType.ExplodedPie、ChartType.ExplodedPie3D、ChartType.Pie、ChartType.Pie3D、ChartType.PieOfPie；或对于其他图表类型，对应于 Chart.ChartData.Series[index]。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回：**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public final int getCount()
```


获取图例条目的数量。只读 int。

**返回：**
int
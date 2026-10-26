---
title: ILegendEntryCollection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示图例集合。
type: docs
url: /zh/com.aspose.slides/ilegendentrycollection/
---```
public interface ILegendEntryCollection
```

表示图例集合。
## 方法

| 方法 | 说明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 获取对应于 Chart.ChartData.Series[0].DataPoints[index] 的图例条目的属性，前提是图表类型属于以下列表：ChartType.BarOfPie、ChartType.ExplodedPie、ChartType.ExplodedPie3D、ChartType.Pie、ChartType.Pie3D、ChartType.PieOfPie；或者对于其他图表类型，对应于 Chart.ChartData.Series[index] 的图例条目属性。 |
| [getCount()](#getCount--) | 获取集合中实际包含的元素数量。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILegendEntryProperties get_Item(int index)
```

获取对应于 Chart.ChartData.Series[0].DataPoints[index] 的图例条目的属性，前提是图表类型属于以下列表：ChartType.BarOfPie、ChartType.ExplodedPie、ChartType.ExplodedPie3D、ChartType.Pie、ChartType.Pie3D、ChartType.PieOfPie；或者对于其他图表类型，对应于 Chart.ChartData.Series[index] 的图例条目属性。

**参数:**  
| 参数 | 类型 | 说明 |
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
---
title: ILegendEntryCollection
second_title: Aspose.Slides for Java API Reference
description:  Represents legends collection.
type: docs
weight: 847
url: /java/com.aspose.slides/ilegendentrycollection/
---```
public interface ILegendEntryCollection
```

Represents legends collection.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets properties of the legend entry corresponding to Chart.ChartData.Series[0].DataPoints[index] in case of chart type from this list: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; or corresponding to Chart.ChartData.Series[index] for other chart types. |
| [getCount()](#getCount--) | Gets the number of elements actually contained in the collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILegendEntryProperties get_Item(int index)
```


Gets properties of the legend entry corresponding to Chart.ChartData.Series[0].DataPoints[index] in case of chart type from this list: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; or corresponding to Chart.ChartData.Series[index] for other chart types.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Gets the number of elements actually contained in the collection. Read-only int.

**Returns:**
int

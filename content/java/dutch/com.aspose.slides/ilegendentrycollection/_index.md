---
title: ILegendEntryCollection
second_title: Aspose.Slides for Java API Reference
description: Represents legends collection.
type: docs
url: /nl/com.aspose.slides/ilegendentrycollection/
---```
public interface ILegendEntryCollection
```

Stelt een verzameling legenden voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Haalt de eigenschappen op van het legend-item dat overeenkomt met Chart.ChartData.Series[0].DataPoints[index] voor grafiektype uit deze lijst: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; of dat overeenkomt met Chart.ChartData.Series[index] voor andere grafiektype. |
| [getCount()](#getCount--) | Haalt het aantal elementen op dat feitelijk in de collectie aanwezig is. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILegendEntryProperties get_Item(int index)
```

Haalt de eigenschappen op van het legend-item dat overeenkomt met Chart.ChartData.Series[0].DataPoints[index] voor grafiektype uit deze lijst: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; of dat overeenkomt met Chart.ChartData.Series[index] voor andere grafiektype.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retourwaarde:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Haalt het aantal elementen op dat feitelijk in de collectie aanwezig is. Alleen-lezen int.

**Retourwaarde:**
int
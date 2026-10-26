---
title: ILegendEntryCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Vertegenwoordigt een collectie legenden.
type: docs
url: /nl/com.aspose.slides/ilegendentrycollection/
---```
public interface ILegendEntryCollection
```

Vertegenwoordigt een collectie legenden.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Haalt de eigenschappen op van het legende-item dat overeenkomt met Chart.ChartData.Series[0].DataPoints[index] bij een grafiektype uit deze lijst: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; of die overeenkomt met Chart.ChartData.Series[index] voor andere grafiektypen. |
| [getCount()](#getCount--) | Haalt het aantal elementen op dat daadwerkelijk in de collectie aanwezig is. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILegendEntryProperties get_Item(int index)
```

Haalt de eigenschappen op van het legende-item dat overeenkomt met Chart.ChartData.Series[0].DataPoints[index] bij een grafiektype uit deze lijst: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; of die overeenkomt met Chart.ChartData.Series[index] voor andere grafiektype-n.

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

Haalt het aantal elementen op dat daadwerkelijk in de collectie aanwezig is. Alleen-lezen int.

**Retourwaarde:**
int
---
title: LegendEntryCollection
second_title: Aspose.Slides för Java API-referens
description: Representerar legendsamlingen.
type: docs
url: /sv/com.aspose.slides/legendentrycollection/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)
```
public class LegendEntryCollection implements ILegendEntryCollection
```

Representerar legendsamlingen.
## Metoder

| Method | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Hämtar egenskaper för legendposten som motsvarar Chart.ChartData.Series[0].DataPoints[index] när diagramtypen är någon av följande: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; eller motsvarande Chart.ChartData.Series[index] för andra diagramtyper. |
| [getCount()](#getCount--) | Hämtar antalet legendposter. |
### get_Item(int index) {#get-Item-int-}
```
public final ILegendEntryProperties get_Item(int index)
```


Hämtar egenskaper för legendposten som motsvarar Chart.ChartData.Series[0].DataPoints[index] när diagramtypen är någon av följande: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; eller motsvarande Chart.ChartData.Series[index] för andra diagramtyper.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public final int getCount()
```


Hämtar antalet legendposter. Skrivskyddad int.

**Returnerar:**
int
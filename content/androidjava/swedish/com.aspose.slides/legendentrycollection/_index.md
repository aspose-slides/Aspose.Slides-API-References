---
title: LegendEntryCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling legender.
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

Representerar en samling med legender.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Hämtar egenskaperna för legendelementet som motsvarar Chart.ChartData.Series[0].DataPoints[index] för diagramtyper från följande lista: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; eller motsvarande Chart.ChartData.Series[index] för andra diagramtyper. |
| [getCount()](#getCount--) | Hämtar antalet legendelement. |
### get_Item(int index) {#get-Item-int-}
```
public final ILegendEntryProperties get_Item(int index)
```


Hämtar egenskaperna för legendelementet som motsvarar Chart.ChartData.Series[0].DataPoints[index] för diagramtyper från följande lista: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; eller motsvarande Chart.ChartData.Series[index] för andra diagramtyper.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public final int getCount()
```


Hämtar antalet legendelement. Skrivskyddad int.

**Returnerar:**
int
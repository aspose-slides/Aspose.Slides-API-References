---
title: ILegendEntryCollection
second_title: Aspose.Slides for Java API Reference
description: Representerar legendsamling.
type: docs
url: /sv/com.aspose.slides/ilegendentrycollection/
---```
public interface ILegendEntryCollection
```

Representerar legendsamling.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Hämtar egenskaper för legendposten som motsvarar Chart.ChartData.Series[0].DataPoints[index] för diagramtyper från denna lista: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; eller motsvarande Chart.ChartData.Series[index] för andra diagramtyper. |
| [getCount()](#getCount--) | Hämtar antalet element som faktiskt finns i samlingen. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILegendEntryProperties get_Item(int index)
```


Hämtar egenskaper för legendposten som motsvarar Chart.ChartData.Series[0].DataPoints[index] för diagramtyper från denna lista: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; eller motsvarande Chart.ChartData.Series[index] för andra diagramtyper.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Hämtar antalet element som faktiskt finns i samlingen. Skrivskyddad int.

**Returnerar:**
int
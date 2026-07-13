---
title: LegendEntryCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een legenda-collectie voor.
type: docs
url: /nl/com.aspose.slides/legendentrycollection/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)
```
public class LegendEntryCollection implements ILegendEntryCollection
```

Stelt een legenda-collectie voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Haalt de eigenschappen op van het legendagelement dat overeenkomt met Chart.ChartData.Series[0].DataPoints[index] in het geval van een grafiektype uit deze lijst: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; of overeenkomt met Chart.ChartData.Series[index] voor andere grafiektype. |
| [getCount()](#getCount--) | Haalt het aantal legende-items op. |
### get_Item(int index) {#get-Item-int-}
```
public final ILegendEntryProperties get_Item(int index)
```

Haalt de eigenschappen op van het legendagelement dat overeenkomt met Chart.ChartData.Series[0].DataPoints[index] in het geval van een grafiektype uit deze lijst: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; of overeenkomt met Chart.ChartData.Series[index] voor andere grafiektype.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retour:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public final int getCount()
```

Haalt het aantal legende-items op. Alleen-lezen int.

**Retour:**
int
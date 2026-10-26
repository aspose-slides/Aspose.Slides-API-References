---
title: LegendEntryCollection
second_title: Aspose.Slides für Java API Referenz
description: Stellt eine Legenden-Sammlung dar.
type: docs
url: /de/com.aspose.slides/legendentrycollection/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)
```
public class LegendEntryCollection implements ILegendEntryCollection
```

Stellt eine Legenden-Sammlung dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ruft die Eigenschaften des Legendeneintrags ab, der Chart.ChartData.Series[0].DataPoints[index] entspricht, falls der Diagrammtyp einer der folgenden ist: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; oder dem Chart.ChartData.Series[index] für andere Diagrammtypen. |
| [getCount()](#getCount--) | Ruft die Anzahl der Legendeneinträge ab. |
### get_Item(int index) {#get-Item-int-}
```
public final ILegendEntryProperties get_Item(int index)
```


Ruft die Eigenschaften des Legendeneintrags ab, der Chart.ChartData.Series[0].DataPoints[index] entspricht, falls der Diagrammtyp einer der folgenden ist: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; oder dem Chart.ChartData.Series[index] für andere Diagrammtypen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public final int getCount()
```


Ruft die Anzahl der Legendeneinträge ab. Nur-Lese int.

**Rückgabe:**
int
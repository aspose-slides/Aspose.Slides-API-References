---
title: LegendEntryCollection
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt die Legenden-Sammlung dar.
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

Stellt die Legenden-Sammlung dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ruft die Eigenschaften des Legenden-Eintrags ab, der zu Chart.ChartData.Series[0].DataPoints[index] gehört, wenn der Diagrammtyp aus dieser Liste stammt: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; oder zu Chart.ChartData.Series[index] für andere Diagrammtypen. |
| [getCount()](#getCount--) | Ruft die Anzahl der Legenden-Einträge ab. |

### get_Item(int index) {#get-Item-int-}
```
public final ILegendEntryProperties get_Item(int index)
```

Ruft die Eigenschaften des Legenden-Eintrags ab, der zu Chart.ChartData.Series[0].DataPoints[index] gehört, wenn der Diagrammtyp aus dieser Liste stammt: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; oder zu Chart.ChartData.Series[index] für andere Diagrammtypen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getCount() {#getCount--}
```
public final int getCount()
```

Ruft die Anzahl der Legenden-Einträge ab. Nur lesbar int.

**Rückgabewert:**
int
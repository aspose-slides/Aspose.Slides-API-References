---
title: ILegendEntryCollection
second_title: Aspose.Slides for Java API Reference
description: Represents legends collection.
type: docs
url: /de/com.aspose.slides/ilegendentrycollection/
---```
public interface ILegendEntryCollection
```

Stellt die Legendenkollektion dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Liefert die Eigenschaften des Legendeneintrags, der der Chart.ChartData.Series[0].DataPoints[index] entspricht, falls der Diagrammtyp aus dieser Liste stammt: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; oder dem Chart.ChartData.Series[index] für andere Diagrammtypen. |
| [getCount()](#getCount--) | Liefert die tatsächlich in der Sammlung enthaltene Elementanzahl. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILegendEntryProperties get_Item(int index)
```

Liefert die Eigenschaften des Legendeneintrags, der der Chart.ChartData.Series[0].DataPoints[index] entspricht, falls der Diagrammtyp aus dieser Liste stammt: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; oder dem Chart.ChartData.Series[index] für andere Diagrammtypen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Liefert die tatsächlich in der Sammlung enthaltene Elementanzahl. Nur lesbarer int.

**Rückgabewert:**
int
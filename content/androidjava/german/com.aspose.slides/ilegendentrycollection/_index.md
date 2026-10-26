---
title: ILegendEntryCollection
second_title: Aspose.Slides für Android via Java API Reference
description: Stellt die Legenden-Sammlung dar.
type: docs
url: /de/com.aspose.slides/ilegendentrycollection/
---```
public interface ILegendEntryCollection
```

Stellt die Legenden-Sammlung dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ruft die Eigenschaften des Legendeneintrags ab, der dem Chart.ChartData.Series[0].DataPoints[index] entspricht, falls der Diagrammtyp aus dieser Liste stammt: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; oder dem Chart.ChartData.Series[index] für andere Diagrammtypen. |
| [getCount()](#getCount--) | Ruft die tatsächlich in der Sammlung enthaltene Anzahl von Elementen ab. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILegendEntryProperties get_Item(int index)
```


Ruft die Eigenschaften des Legendeneintrags ab, der dem Chart.ChartData.Series[0].DataPoints[index] entspricht, falls der Diagrammtyp aus dieser Liste stammt: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; oder dem Chart.ChartData.Series[index] für andere Diagrammtypen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Ruft die tatsächlich in der Sammlung enthaltene Anzahl von Elementen ab. Nur-Lese int.

**Rückgabe:**
int
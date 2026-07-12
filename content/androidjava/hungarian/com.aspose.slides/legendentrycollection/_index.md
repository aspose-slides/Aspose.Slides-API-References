---
title: LegendEntryCollection
second_title: Aspose.Slides Android számára Java API hivatkozás
description: A jelmagyarázatok gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/legendentrycollection/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)
```
public class LegendEntryCollection implements ILegendEntryCollection
```

A jelmagyarázatok gyűjteményét képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lekéri a jelmagyarázat bejegyzésének tulajdonságait, amely a Chart.ChartData.Series[0].DataPoints[index] elemhez tartozik, ha a diagram típusa az alábbi listából származik: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; vagy a Chart.ChartData.Series[index] elemhez tartozik más diagramtípusok esetén. |
| [getCount()](#getCount--) | Lekéri a jelmagyarázat bejegyzéseinek számát. |
### get_Item(int index) {#get-Item-int-}
```
public final ILegendEntryProperties get_Item(int index)
```


Lekéri a jelmagyarázat bejegyzésének tulajdonságait, amely a Chart.ChartData.Series[0].DataPoints[index] elemhez tartozik, ha a diagram típusa az alábbi listából származik: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; vagy a Chart.ChartData.Series[index] elemhez tartozik más diagramtípusok esetén.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public final int getCount()
```


Lekéri a jelmagyarázat bejegyzéseinek számát. Csak olvasható int.

**Visszatérési érték:**
int
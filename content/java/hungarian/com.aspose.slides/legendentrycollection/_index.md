---
title: LegendEntryCollection
second_title: Aspose.Slides Java API hivatkozás
description: A legendák gyűjteményét ábrázolja.
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

A legendák gyűjteményét ábrázolja.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lekéri a legendabejegyzés tulajdonságait, amely a Chart.ChartData.Series[0].DataPoints[index] elemhez tartozik a következő diagramtípusok egyikén: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; vagy a Chart.ChartData.Series[index] elemhez tartozik más diagramtípusok esetén. |
| [getCount()](#getCount--) | Lekéri a legendabejegyzések számát. |
### get_Item(int index) {#get-Item-int-}
```
public final ILegendEntryProperties get_Item(int index)
```

Lekéri a legendabejegyzés tulajdonságait, amely a Chart.ChartData.Series[0].DataPoints[index] elemhez tartozik a következő diagramtípusok egyikén: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; vagy a Chart.ChartData.Series[index] elemhez tartozik más diagramtípusok esetén.

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

Lekéri a legendabejegyzések számát. Csak olvasható int.

**Visszatérési érték:**
int
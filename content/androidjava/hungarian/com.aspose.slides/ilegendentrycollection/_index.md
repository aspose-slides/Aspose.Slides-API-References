---
title: ILegendEntryCollection
second_title: Aspose.Slides for Android via Java API Reference
description: A jelmagyarázatok gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/ilegendentrycollection/
---```
public interface ILegendEntryCollection
```

A jelmagyarázatok gyűjteményét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | A legend entry-hez tartozó tulajdonságokat adja vissza, amely a Chart.ChartData.Series[0].DataPoints[index] elemhez tartozik a következő diagramtípusok esetén: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; vagy a Chart.ChartData.Series[index] elemhez a többi diagramtípus esetén. |
| [getCount()](#getCount--) | A gyűjteményben ténylegesen lévő elemek számát adja vissza. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILegendEntryProperties get_Item(int index)
```

A legend entry-hez tartozó tulajdonságokat adja vissza, amely a Chart.ChartData.Series[0].DataPoints[index] elemhez tartozik a következő diagramtípusok esetén: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; vagy a Chart.ChartData.Series[index] elemhez a többi diagramtípus esetén.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public abstract int getCount()
```

A gyűjteményben ténylegesen lévő elemek számát adja vissza. Csak olvasható int.

**Visszatérési érték:**
int
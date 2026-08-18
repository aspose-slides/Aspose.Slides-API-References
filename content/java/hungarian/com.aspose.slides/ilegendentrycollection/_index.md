---
title: ILegendEntryCollection
second_title: Aspose.Slides for Java API Reference
description: A legendákat tartalmazó gyűjtemény.
type: docs
url: /hu/com.aspose.slides/ilegendentrycollection/
---```
public interface ILegendEntryCollection
```

A legendákat tartalmazó gyűjtemény.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | A legendabejegyzés tulajdonságait adja vissza, amely a Chart.ChartData.Series[0].DataPoints[index] elemhez tartozik, ha a diagram típusa az alábbi listából származik: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; vagy a Chart.ChartData.Series[index] elemhez tartozik más diagramtípusok esetén. |
| [getCount()](#getCount--) | A gyűjteményben ténylegesen lévő elemek számát adja vissza. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILegendEntryProperties get_Item(int index)
```

A legendabejegyzés tulajdonságait adja vissza, amely a Chart.ChartData.Series[0].DataPoints[index] elemhez tartozik, ha a diagram típusa az alábbi listából származik: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; vagy a Chart.ChartData.Series[index] elemhez tartozik más diagramtípusok esetén.

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
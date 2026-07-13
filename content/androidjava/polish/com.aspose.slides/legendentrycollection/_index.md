---
title: LegendEntryCollection
second_title: Aspose.Slides dla Androida - odwołanie API Java
description: Reprezentuje kolekcję legend.
type: docs
url: /pl/com.aspose.slides/legendentrycollection/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)
```
public class LegendEntryCollection implements ILegendEntryCollection
```

Reprezentuje kolekcję legend.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Pobiera właściwości elementu legendy odpowiadającego Chart.ChartData.Series[0].DataPoints[index] w przypadku typu wykresu z tej listy: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; lub odpowiadającego Chart.ChartData.Series[index] dla innych typów wykresów. |
| [getCount()](#getCount--) | Pobiera liczbę elementów legendy. |
### get_Item(int index) {#get-Item-int-}
```
public final ILegendEntryProperties get_Item(int index)
```

Pobiera właściwości elementu legendy odpowiadającego Chart.ChartData.Series[0].DataPoints[index] w przypadku typu wykresu z tej listy: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; lub odpowiadającego Chart.ChartData.Series[index] dla innych typów wykresów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public final int getCount()
```

Pobiera liczbę elementów legendy. Tylko do odczytu int.

**Zwraca:**
int
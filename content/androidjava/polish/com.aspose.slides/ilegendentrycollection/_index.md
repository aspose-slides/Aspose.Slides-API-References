---
title: ILegendEntryCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents legends collection.
type: docs
url: /pl/com.aspose.slides/ilegendentrycollection/
---```
public interface ILegendEntryCollection
```

Reprezentuje kolekcję legend.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Pobiera właściwości pozycji legendy odpowiadającej Chart.ChartData.Series[0].DataPoints[index] w przypadku typu wykresu z tej listy: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; lub odpowiadającej Chart.ChartData.Series[index] dla innych typów wykresów. |
| [getCount()](#getCount--) | Pobiera liczbę elementów faktycznie zawartych w kolekcji. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILegendEntryProperties get_Item(int index)
```

Pobiera właściwości pozycji legendy odpowiadającej Chart.ChartData.Series[0].DataPoints[index] w przypadku typu wykresu z tej listy: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; lub odpowiadającej Chart.ChartData.Series[index] dla innych typów wykresów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Pobiera liczbę elementów faktycznie zawartych w kolekcji. int tylko do odczytu.

**Zwraca:**
int
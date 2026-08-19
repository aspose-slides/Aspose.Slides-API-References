---
title: LegendEntryCollection
second_title: Aspose.Slides pro Java - referenční příručka API
description: Zastupuje kolekci legend.
type: docs
url: /cs/com.aspose.slides/legendentrycollection/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)
```
public class LegendEntryCollection implements ILegendEntryCollection
```

Zastupuje kolekci legend.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Získá vlastnosti položky legendy odpovídající Chart.ChartData.Series[0].DataPoints[index] v případě typu grafu ze seznamu: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; nebo odpovídající Chart.ChartData.Series[index] pro ostatní typy grafu. |
| [getCount()](#getCount--) | Získá počet položek legendy. |
### get_Item(int index) {#get-Item-int-}
```
public final ILegendEntryProperties get_Item(int index)
```

Získá vlastnosti položky legendy odpovídající Chart.ChartData.Series[0].DataPoints[index] v případě typu grafu ze seznamu: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; nebo odpovídající Chart.ChartData.Series[index] pro ostatní typy grafu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Návratová hodnota:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public final int getCount()
```

Získá počet položek legendy. Pouze pro čtení int.

**Návratová hodnota:**
int
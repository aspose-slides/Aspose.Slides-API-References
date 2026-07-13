---
title: LegendEntryCollection
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje kolekci legend.
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

Reprezentuje kolekci legend.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Získá vlastnosti položky legendy odpovídající Chart.ChartData.Series[0].DataPoints[index] v případě typu grafu z tohoto seznamu: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; nebo odpovídající Chart.ChartData.Series[index] pro jiné typy grafů. |
| [getCount()](#getCount--) | Získá počet položek legendy. |
### get_Item(int index) {#get-Item-int-}
```
public final ILegendEntryProperties get_Item(int index)
```

Získá vlastnosti položky legendy odpovídající Chart.ChartData.Series[0].DataPoints[index] v případě typu grafu z tohoto seznamu: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; nebo odpovídající Chart.ChartData.Series[index] pro jiné typy grafů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public final int getCount()
```

Získá počet položek legendy. Pouze ke čtení int.

**Vrací:**
int
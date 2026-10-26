---
title: ILegendEntryCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents legends collection.
type: docs
url: /cs/com.aspose.slides/ilegendentrycollection/
---```
public interface ILegendEntryCollection
```

Reprezentuje kolekci legend.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Získá vlastnosti položky legendy odpovídající Chart.ChartData.Series[0].DataPoints[index] v případě typu grafu z tohoto seznamu: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; nebo odpovídající Chart.ChartData.Series[index] pro ostatní typy grafů. |
| [getCount()](#getCount--) | Získá počet prvků ve skutečnosti obsažených v kolekci. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILegendEntryProperties get_Item(int index)
```


Získá vlastnosti položky legendy odpovídající Chart.ChartData.Series[0].DataPoints[index] v případě typu grafu z tohoto seznamu: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; nebo odpovídající Chart.ChartData.Series[index] pro ostatní typy grafů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Návratová hodnota:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Získá počet prvků ve skutečnosti obsažených v kolekci. Pouze pro čtení int.

**Návratová hodnota:**
int
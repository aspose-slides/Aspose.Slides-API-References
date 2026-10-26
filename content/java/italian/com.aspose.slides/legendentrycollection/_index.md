---
title: LegendEntryCollection
second_title: Riferimento API Aspose.Slides per Java
description: Rappresenta la collezione di legende.
type: docs
url: /it/com.aspose.slides/legendentrycollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)
```
public class LegendEntryCollection implements ILegendEntryCollection
```

Rappresenta la collezione di legende.
## Methods

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ottiene le proprietà della voce della legenda corrispondente a Chart.ChartData.Series[0].DataPoints[index] nel caso di un tipo di grafico da questo elenco: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; o corrispondente a Chart.ChartData.Series[index] per altri tipi di grafico. |
| [getCount()](#getCount--) | Ottiene il numero di voci della legenda. |
### get_Item(int index) {#get-Item-int-}
```
public final ILegendEntryProperties get_Item(int index)
```

Ottiene le proprietà della voce della legenda corrispondente a Chart.ChartData.Series[0].DataPoints[index] nel caso di un tipo di grafico da questo elenco: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; o corrispondente a Chart.ChartData.Series[index] per altri tipi di grafico.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Returns:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public final int getCount()
```

Ottiene il numero di voci della legenda. Solo lettura int.

**Returns:**
int
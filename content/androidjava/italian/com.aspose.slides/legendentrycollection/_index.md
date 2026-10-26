---
title: LegendEntryCollection
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta la raccolta di legende.
type: docs
url: /it/com.aspose.slides/legendentrycollection/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)
```
public class LegendEntryCollection implements ILegendEntryCollection
```

Rappresenta la raccolta di legende.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ottiene le proprietà della voce della legenda corrispondente a Chart.ChartData.Series[0].DataPoints[index] nel caso di un tipo di grafico presente in questo elenco: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; oppure corrispondente a Chart.ChartData.Series[index] per gli altri tipi di grafico. |
| [getCount()](#getCount--) | Ottiene il numero di voci della legenda. |
### get_Item(int index) {#get-Item-int-}
```
public final ILegendEntryProperties get_Item(int index)
```


Ottiene le proprietà della voce della legenda corrispondente a Chart.ChartData.Series[0].DataPoints[index] nel caso di un tipo di grafico presente in questo elenco: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; oppure corrispondente a Chart.ChartData.Series[index] per gli altri tipi di grafico.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public final int getCount()
```


Ottiene il numero di voci della legenda. int di sola lettura.

**Restituisce:**
int
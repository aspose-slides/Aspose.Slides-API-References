---
title: ILegendEntryCollection
second_title: Aspose.Slides for Java API Reference
description: Rappresenta la raccolta di leggende.
type: docs
url: /it/com.aspose.slides/ilegendentrycollection/
---```
public interface ILegendEntryCollection
```

Rappresenta la raccolta di leggende.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ottiene le proprietà della voce della legenda corrispondente a Chart.ChartData.Series[0].DataPoints[index] nel caso di un tipo di grafico presente in questo elenco: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; o corrispondente a Chart.ChartData.Series[index] per altri tipi di grafico. |
| [getCount()](#getCount--) | Ottiene il numero di elementi effettivamente contenuti nella raccolta. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILegendEntryProperties get_Item(int index)
```


Ottiene le proprietà della voce della legenda corrispondente a Chart.ChartData.Series[0].DataPoints[index] nel caso di un tipo di grafico presente in questo elenco: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; o corrispondente a Chart.ChartData.Series[index] per altri tipi di grafico.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Ottiene il numero di elementi effettivamente contenuti nella raccolta. Solo lettura int.

**Restituisce:**
int
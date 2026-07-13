---
title: ILegendEntryCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Rappresenta la raccolta di legende.
type: docs
url: /it/com.aspose.slides/ilegendentrycollection/
---```
public interface ILegendEntryCollection
```

Rappresenta la raccolta di legende.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ottiene le proprietà della voce della leggenda corrispondente a Chart.ChartData.Series[0].DataPoints[index] nel caso di tipo di grafico appartenente a questo elenco: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; o corrispondente a Chart.ChartData.Series[index] per altri tipi di grafico. |
| [getCount()](#getCount--) | Ottiene il numero di elementi effettivamente contenuti nella raccolta. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILegendEntryProperties get_Item(int index)
```

Ottiene le proprietà della voce della leggenda corrispondente a Chart.ChartData.Series[0].DataPoints[index] nel caso di tipo di grafico appartenente a questo elenco: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; o corrispondente a Chart.ChartData.Series[index] per altri tipi di grafico.

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

Ottiene il numero di elementi effettivamente contenuti nella raccolta. int di sola lettura.

**Restituisce:**
int
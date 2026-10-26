---
title: ILegendEntryCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Representa a coleção de legendas.
type: docs
url: /pt/com.aspose.slides/ilegendentrycollection/
---```
public interface ILegendEntryCollection
```

Representa a coleção de legendas.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtém as propriedades da entrada de legenda correspondente a Chart.ChartData.Series[0].DataPoints[index] no caso de tipo de gráfico desta lista: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; ou correspondente a Chart.ChartData.Series[index] para outros tipos de gráfico. |
| [getCount()](#getCount--) | Obtém o número de elementos realmente contidos na coleção. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILegendEntryProperties get_Item(int index)
```

Obtém as propriedades da entrada de legenda correspondente a Chart.ChartData.Series[0].DataPoints[index] no caso de tipo de gráfico desta lista: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; ou correspondente a Chart.ChartData.Series[index] para outros tipos de gráfico.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorno:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Obtém o número de elementos realmente contidos na coleção. Somente leitura int.

**Retorno:**
int
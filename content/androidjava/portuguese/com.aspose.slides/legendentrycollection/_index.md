---
title: LegendEntryCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa a coleção de legendas.
type: docs
url: /pt/com.aspose.slides/legendentrycollection/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)
```
public class LegendEntryCollection implements ILegendEntryCollection
```

Representa a coleção de legendas.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtém propriedades da entrada da legenda correspondente a Chart.ChartData.Series[0].DataPoints[index] no caso de tipo de gráfico desta lista: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; ou correspondente a Chart.ChartData.Series[index] para outros tipos de gráfico. |
| [getCount()](#getCount--) | Obtém o número de entradas de legenda. |
### get_Item(int index) {#get-Item-int-}
```
public final ILegendEntryProperties get_Item(int index)
```


Obtém propriedades da entrada da legenda correspondente a Chart.ChartData.Series[0].DataPoints[index] no caso de tipo de gráfico desta lista: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; ou correspondente a Chart.ChartData.Series[index] para outros tipos de gráfico.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public final int getCount()
```


Obtém o número de entradas de legenda. int somente leitura.

**Retorna:**
int
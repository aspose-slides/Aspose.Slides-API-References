---
title: LegendEntryCollection
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Representa la colección de leyendas.
type: docs
url: /es/com.aspose.slides/legendentrycollection/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)
```
public class LegendEntryCollection implements ILegendEntryCollection
```

Representa la colección de leyendas.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtiene las propiedades de la entrada de leyenda correspondiente a Chart.ChartData.Series[0].DataPoints[index] en caso de que el tipo de gráfico sea de esta lista: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; o correspondiente a Chart.ChartData.Series[index] para otros tipos de gráfico. |
| [getCount()](#getCount--) | Obtiene el número de entradas de leyenda. |
### get_Item(int index) {#get-Item-int-}
```
public final ILegendEntryProperties get_Item(int index)
```


Obtiene las propiedades de la entrada de leyenda correspondiente a Chart.ChartData.Series[0].DataPoints[index] en caso de que el tipo de gráfico sea de esta lista: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; o correspondiente a Chart.ChartData.Series[index] para otros tipos de gráfico.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public final int getCount()
```


Obtiene el número de entradas de leyenda. int de solo lectura.

**Devuelve:**
int
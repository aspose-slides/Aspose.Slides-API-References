---
title: ILegendEntryCollection
second_title: Aspose.Slides para Android mediante la referencia de la API Java
description: Representa la colección de leyendas.
type: docs
url: /es/com.aspose.slides/ilegendentrycollection/
---```
public interface ILegendEntryCollection
```

Representa la colección de leyendas.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtiene las propiedades de la entrada de leyenda correspondiente a Chart.ChartData.Series[0].DataPoints[index] en caso de que el tipo de gráfico sea de esta lista: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; o correspondiente a Chart.ChartData.Series[index] para otros tipos de gráfico. |
| [getCount()](#getCount--) | Obtiene el número de elementos realmente contenidos en la colección. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILegendEntryProperties get_Item(int index)
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
public abstract int getCount()
```

Obtiene el número de elementos realmente contenidos en la colección. Solo lectura int.

**Devuelve:**
int
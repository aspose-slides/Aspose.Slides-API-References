---
title: IChartSeriesGroupCollection
second_title: Referencia de API de Aspose.Slides para Java
description: Representa la colección de grupos de series combinables.
type: docs
url: /es/com.aspose.slides/ichartseriesgroupcollection/
---
**Todas las interfaces implementadas:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesGroupCollection extends IGenericCollection<IChartSeriesGroup>
```

Representa la colección de grupos de series combinables.

--------------------

1) Cada grupo de series contiene series con tipos combinables. Los grupos de tipos de series combinables se definen y describen con el enumerado CombinableSeriesTypesGroup. Además, cada grupo de series contiene series que se trazan ya sea en ejes principales o en ejes secundarios (no ambos casos en un mismo grupo). Por lo tanto, el principio de agrupamiento de series es un agrupamiento por los tipos de grupos mencionados anteriormente y por el tipo de trazado principal/secundario. 2) El grupo de series contiene algunas propiedades de series que son comunes para cada serie en el grupo ("propiedades del grupo de series"). Las "propiedades del grupo de series" en la clase ChartSeriesGroup son de lectura/escritura. Cada una de las "propiedades del grupo de series" puede tener una proyección de solo lectura en la clase ChartSeries.

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(IChartSeries ofSeries)](#get-Item-com.aspose.slides.IChartSeries-) | Obtiene el grupo de series por serie. |
| [get_Item(int index)](#get-Item-int-) | Obtiene el grupo de series por índice. |
### get_Item(IChartSeries ofSeries) {#get-Item-com.aspose.slides.IChartSeries-}
```
public abstract IChartSeriesGroup get_Item(IChartSeries ofSeries)
```


Obtiene el grupo de series por serie.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ofSeries | [IChartSeries](../../com.aspose.slides/ichartseries) |  |

**Devuelve:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeriesGroup get_Item(int index)
```


Obtiene el grupo de series por índice.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
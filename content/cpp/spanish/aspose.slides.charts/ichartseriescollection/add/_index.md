---
title: Add()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea nuevas series de gráfico y las agrega a la colección.
type: docs
weight: 14
url: /es/aspose.slides.charts/ichartseriescollection/add/
---
## IChartSeriesCollection::Add(ChartType) method


Crea una nueva serie de gráfico y la agrega a la colección.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(ChartType type)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | Tipo de serie |

### Valor de retorno

Nueva serie de gráfico.

## IChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) method


Crea una nueva serie de gráfico a partir de [IChartDataCell](../../ichartdatacell/) y la agrega a la colección.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) que contiene el nombre de la serie. |
| type | [ChartType](../../charttype/) | Tipo que establece el tipo de la serie |

### Valor de retorno

Serie de gráfico añadida o serie que ya está en la colección.
## Observaciones


Si la serie de gráfico se creó a partir de la misma celda que ya está en la colección, entonces el método no agrega nada y devuelve su índice.



## IChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) method


Crea una nueva serie de gráfico a partir de [IChartCellCollection](../../ichartcellcollection/) y la agrega a la colección.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | Celdas que contienen el nombre de la serie. |
| type | [ChartType](../../charttype/) | Tipo que establece el tipo de la serie |

### Valor de retorno

Serie de gráfico añadida o serie que ya está en la colección.
## Observaciones


Si la serie de gráfico se creó a partir de la misma celda que ya está en la colección, entonces el método no agrega nada y devuelve su índice.



## IChartSeriesCollection::Add(System::String, ChartType) method


Crea una nueva serie de gráfico a partir de un valor y la agrega a la colección.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::String name, ChartType type)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | Nombre de la serie. |
| type | [ChartType](../../charttype/) | Tipo que establece el tipo de la serie |

### Valor de retorno

Serie de gráfico añadida.



## Ver también

* Enum [ChartType](../../charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartSeries](../../ichartseries/)
* Class [IChartSeriesCollection](../)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [IChartCellCollection](../../ichartcellcollection/)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
---
title: Add()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea nuevas series de gráfico y las agrega a la colección.
type: docs
weight: 53
url: /es/aspose.slides.charts/chartseriescollection/add/
---
## ChartSeriesCollection::Add(ChartType) método

Crea una nueva serie de gráfico y la agrega a la colección.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(ChartType type) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | Tipo de serie |

### Valor devuelto

Nueva serie de gráfico.

## ChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) método

Crea una nueva serie de gráfico a partir de [ChartDataCell](../../chartdatacell/) y la agrega a la colección.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) que contiene el nombre de la serie. |
| type | [ChartType](../../charttype/) | Tipo establecido de serie |

### Valor devuelto

Serie de gráfico agregada o serie que ya está en la colección.

## Comentarios

Si la serie de gráfico se creó a partir de la misma celda que ya está en la colección, entonces el método no agrega nada y devuelve su índice.

## ChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) método

Crea una nueva serie de gráfico a partir de [ChartCellCollection](../../chartcellcollection/) y la agrega a la colección.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | Celdas que contienen el nombre de la serie. |
| type | [ChartType](../../charttype/) | Tipo establecido de serie |

### Valor devuelto

Serie de gráfico agregada o serie que ya está en la colección.

## Comentarios

Si la serie de gráfico se creó a partir de la misma celda que ya está en la colección, entonces el método no agrega nada y devuelve su índice.

## ChartSeriesCollection::Add(System::String, ChartType) método

Crea una nueva serie de gráfico a partir del valor y la agrega a la colección.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::String name, ChartType type) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | Nombre de la serie. |
| type | [ChartType](../../charttype/) | Tipo establecido de serie |

### Valor devuelto

Serie de gráfico agregada.

## Ver también

* Enumeración [ChartType](../../charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IChartSeries](../../ichartseries/)
* Clase [ChartSeriesCollection](../)
* Clase [IChartDataCell](../../ichartdatacell/)
* Clase [IChartCellCollection](../../ichartcellcollection/)
* Clase [String](../../../system/string/)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)
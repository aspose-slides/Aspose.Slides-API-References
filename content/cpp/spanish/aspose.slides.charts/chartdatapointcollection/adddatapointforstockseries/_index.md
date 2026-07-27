---
title: AddDataPointForStockSeries()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Crea el nuevo punto de datos y lo añade al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos de Stock (ver también ChartTypeCharacterizer::IsChartTypeStock(ChartType) método)."
type: docs
weight: 209
url: /es/aspose.slides.charts/chartdatapointcollection/adddatapointforstockseries/
---
## ChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr\<IChartDataCell\>) método


Crea el nuevo punto de datos y lo añade al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos de Stock (ver también el método [ChartTypeCharacterizer::IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/)).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr<IChartDataCell> value) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Valor del punto de datos. |

### Valor devuelto

Nuevo punto de datos.

## ChartDataPointCollection::AddDataPointForStockSeries(double) método


Crea el nuevo punto de datos y lo añade al final de la colección. Aplicable a series cuyo chartType es uno de los subtipos de Stock (ver también el método [ChartTypeCharacterizer::IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/)).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForStockSeries(double value) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | **double** | Valor del punto de datos. |

### Valor devuelto

Nuevo punto de datos.

## Ver también

* Definición de tipo [SharedPtr](../../../system/sharedptr/)
* Clase [IChartDataPoint](../../ichartdatapoint/)
* Clase [IChartDataCell](../../ichartdatacell/)
* Clase [ChartDataPointCollection](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)
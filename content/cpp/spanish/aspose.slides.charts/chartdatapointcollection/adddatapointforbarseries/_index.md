---
title: AddDataPointForBarSeries()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de Column o subtipos de Bar (ver también ChartTypeCharacterizer::IsChartTypeColumn(ChartType) y ChartTypeCharacterizer::IsChartTypeBar(ChartType) método)."
type: docs
weight: 261
url: /es/aspose.slides.charts/chartdatapointcollection/adddatapointforbarseries/
---
## ChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr\<IChartDataCell\>) método

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de [Column](../../../aspose.slides/column/) o subtipos de Bar (ver también [ChartTypeCharacterizer::IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) y [ChartTypeCharacterizer::IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) método).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr<IChartDataCell> value) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Valor del punto de datos |

### Valor devuelto

Nuevo punto de datos.

## ChartDataPointCollection::AddDataPointForBarSeries(double) método

Crea un nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo chartType es uno de [Column](../../../aspose.slides/column/) o subtipos de Bar (ver también [ChartTypeCharacterizer::IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) y [ChartTypeCharacterizer::IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) método).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForBarSeries(double value) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | **double** | Valor del punto de datos |

### Valor devuelto

Nuevo punto de datos.

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IChartDataPoint](../../ichartdatapoint/)
* Clase [IChartDataCell](../../ichartdatacell/)
* Clase [ChartDataPointCollection](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)
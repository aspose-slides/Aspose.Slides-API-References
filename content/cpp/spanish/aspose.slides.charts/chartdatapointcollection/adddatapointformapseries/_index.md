---
title: AddDataPointForMapSeries()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo tipo de gráfico es Map.
type: docs
weight: 417
url: /es/aspose.slides.charts/chartdatapointcollection/adddatapointformapseries/
---
## ChartDataPointCollection::AddDataPointForMapSeries(System::SharedPtr\<IChartDataCell\>) método


Crea el nuevo punto de datos y lo agrega al final de la colección. Aplicable a series cuyo tipo de gráfico es Map.

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForMapSeries(System::SharedPtr<IChartDataCell> value) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | punto de datos ColorValue |

### Valor devuelto

Nuevo punto de datos.
## Observaciones




```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Map, 50.0f, 50.0f, 500.0f, 400.0f, false);
auto wb = chart->get_ChartData()->get_ChartDataWorkbook();

auto series = chart->get_ChartData()->get_Series()->Add(Aspose::Slides::Charts::ChartType::Map);
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B2", System::ObjectExt::Box<int32_t>(5)));
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B3", System::ObjectExt::Box<int32_t>(1)));
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B4", System::ObjectExt::Box<int32_t>(10)));
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IChartDataPoint](../../ichartdatapoint/)
* Clase [IChartDataCell](../../ichartdatacell/)
* Clase [ChartDataPointCollection](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)
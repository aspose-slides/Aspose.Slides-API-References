---
title: get_Label()
second_title: Referencia de API de Aspose.Slides para C++
description: Representa la etiqueta de datos del nivel de punto de datos. Aplicado a los tipos de serie Treemap y Sunburst. Solo lectura IDataLabel.
type: docs
weight: 14
url: /es/aspose.slides.charts/chartdatapointlevel/get_label/
---
## ChartDataPointLevel::get_Label() método


Representa la etiqueta de datos del nivel de punto de datos. Aplicado a los tipos de serie Treemap y Sunburst. Solo lectura [IDataLabel](../../idatalabel/).

```cpp
System::SharedPtr<IDataLabel> Aspose::Slides::Charts::ChartDataPointLevel::get_Label() override
```

## Observaciones



```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Sunburst, 50.0f, 50.0f, 500.0f, 400.0f);
auto series = chart->get_ChartData()->get_Series()->idx_get(0);
auto dataPointLevel = series->get_DataPoints()->idx_get(0)->get_DataPointLevels()->idx_get(1);

dataPointLevel->get_Label()->get_DataLabelFormat()->set_ShowCategoryName(false);
dataPointLevel->get_Label()->get_DataLabelFormat()->set_ShowValue(true);
dataPointLevel->get_Label()->get_DataLabelFormat()->set_ShowSeriesName(true);

dataPointLevel = series->get_DataPoints()->idx_get(12)->get_DataPointLevels()->idx_get(1);
dataPointLevel->get_Label()->get_TextFormat()->get_PortionFormat()->get_FillFormat()->set_FillType(FillType::Solid);
dataPointLevel->get_Label()->get_TextFormat()->get_PortionFormat()->get_FillFormat()->get_SolidFillColor()->set_Color(Color::get_Red());
```

## Ver también

* Definición de tipo [SharedPtr](../../../system/sharedptr/)
* Clase [IDataLabel](../../idatalabel/)
* Clase [ChartDataPointLevel](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)
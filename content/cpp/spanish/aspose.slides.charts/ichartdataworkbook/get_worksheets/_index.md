---
title: get_Worksheets()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtiene una colección de hojas de cálculo.
type: docs
weight: 1
url: /es/aspose.slides.charts/ichartdataworkbook/get_worksheets/
---
## IChartDataWorkbook::get_Worksheets() método


Obtiene una colección de hojas de cálculo.

```cpp
virtual System::SharedPtr<IChartDataWorksheetCollection> Aspose::Slides::Charts::IChartDataWorkbook::get_Worksheets()=0
```

## Observaciones


Ejemplo: 
```cpp
auto pres = System::MakeObject<Presentation>();

auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Pie, 50.0f, 50.0f, 400.0f, 500.0f);
auto workbook = chart->get_ChartData()->get_ChartDataWorkbook();
for (const auto& worksheet : workbook->get_Worksheets())
{
    System::String worksheetName = worksheet->get_Name();
}
```




## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IChartDataWorksheetCollection](../../ichartdataworksheetcollection/)
* Clase [IChartDataWorkbook](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)
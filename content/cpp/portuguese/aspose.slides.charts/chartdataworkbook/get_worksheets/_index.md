---
title: get_Worksheets()
second_title: Referência da API Aspose.Slides para C++
description: Obtém uma coleção de planilhas.
type: docs
weight: 1
url: /pt/aspose.slides.charts/chartdataworkbook/get_worksheets/
---
## ChartDataWorkbook::get_Worksheets() método


Obtém uma coleção de planilhas.

```cpp
System::SharedPtr<IChartDataWorksheetCollection> Aspose::Slides::Charts::ChartDataWorkbook::get_Worksheets() override
```

## Observações


Exemplo: 
```cpp
auto pres = System::MakeObject<Presentation>();

auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Pie, 50.0f, 50.0f, 400.0f, 500.0f);
auto workbook = chart->get_ChartData()->get_ChartDataWorkbook();
for (const auto& worksheet : workbook->get_Worksheets())
{
    System::String worksheetName = worksheet->get_Name();
}
```




## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartDataWorksheetCollection](../../ichartdataworksheetcollection/)
* Classe [ChartDataWorkbook](../)
* Espaço de nomes [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)
---
title: get_Worksheets()
second_title: Riferimento API Aspose.Slides per C++
description: Ottiene una raccolta di fogli di lavoro.
type: docs
weight: 1
url: /it/aspose.slides.charts/chartdataworkbook/get_worksheets/
---
## ChartDataWorkbook::get_Worksheets() metodo


Ottiene una raccolta di fogli di lavoro.

```cpp
System::SharedPtr<IChartDataWorksheetCollection> Aspose::Slides::Charts::ChartDataWorkbook::get_Worksheets() override
```

## Osservazioni


Esempio: 
```cpp
auto pres = System::MakeObject<Presentation>();

auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Pie, 50.0f, 50.0f, 400.0f, 500.0f);
auto workbook = chart->get_ChartData()->get_ChartDataWorkbook();
for (const auto& worksheet : workbook->get_Worksheets())
{
    System::String worksheetName = worksheet->get_Name();
}
```




## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartDataWorksheetCollection](../../ichartdataworksheetcollection/)
* Classe [ChartDataWorkbook](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
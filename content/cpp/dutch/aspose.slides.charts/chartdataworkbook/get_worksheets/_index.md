---
title: get_Worksheets()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een verzameling werkbladen.
type: docs
weight: 1
url: /nl/aspose.slides.charts/chartdataworkbook/get_worksheets/
---
## ChartDataWorkbook::get_Worksheets() methode


Retourneert een verzameling werkbladen.

```cpp
System::SharedPtr<IChartDataWorksheetCollection> Aspose::Slides::Charts::ChartDataWorkbook::get_Worksheets() override
```

## Opmerkingen


Voorbeeld: 
```cpp
auto pres = System::MakeObject<Presentation>();

auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Pie, 50.0f, 50.0f, 400.0f, 500.0f);
auto workbook = chart->get_ChartData()->get_ChartDataWorkbook();
for (const auto& worksheet : workbook->get_Worksheets())
{
    System::String worksheetName = worksheet->get_Name();
}
```




## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChartDataWorksheetCollection](../../ichartdataworksheetcollection/)
* Klasse [ChartDataWorkbook](../)
* Naamruimte [Aspose::Slides::Charts](../../)
* Bibliotheek [Aspose.Slides](../../../)
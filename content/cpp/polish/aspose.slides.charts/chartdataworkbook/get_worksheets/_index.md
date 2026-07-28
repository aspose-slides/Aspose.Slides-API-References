---
title: get_Worksheets()
second_title: Aspose.Slides dla C++ – referencja API
description: Zwraca kolekcję arkuszy.
type: docs
weight: 1
url: /pl/aspose.slides.charts/chartdataworkbook/get_worksheets/
---
## ChartDataWorkbook::get_Worksheets() metoda


Zwraca kolekcję arkuszy.

```cpp
System::SharedPtr<IChartDataWorksheetCollection> Aspose::Slides::Charts::ChartDataWorkbook::get_Worksheets() override
```

## Uwagi


Przykład: 
```cpp
auto pres = System::MakeObject<Presentation>();

auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Pie, 50.0f, 50.0f, 400.0f, 500.0f);
auto workbook = chart->get_ChartData()->get_ChartDataWorkbook();
for (const auto& worksheet : workbook->get_Worksheets())
{
    System::String worksheetName = worksheet->get_Name();
}
```




## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IChartDataWorksheetCollection](../../ichartdataworksheetcollection/)
* Klasa [ChartDataWorkbook](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
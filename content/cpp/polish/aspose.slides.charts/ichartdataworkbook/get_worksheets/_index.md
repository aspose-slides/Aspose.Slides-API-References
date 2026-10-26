---
title: get_Worksheets()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Pobiera kolekcję arkuszy.
type: docs
weight: 1
url: /pl/aspose.slides.charts/ichartdataworkbook/get_worksheets/
---
## IChartDataWorkbook::get_Worksheets() metoda


Pobiera kolekcję arkuszy.

```cpp
virtual System::SharedPtr<IChartDataWorksheetCollection> Aspose::Slides::Charts::IChartDataWorkbook::get_Worksheets()=0
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
* Klasa [IChartDataWorkbook](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)
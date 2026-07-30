---
title: get_Worksheets()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Získá kolekci listů.
type: docs
weight: 1
url: /cs/aspose.slides.charts/chartdataworkbook/get_worksheets/
---
## ChartDataWorkbook::get_Worksheets() metoda


Získá kolekci listů.

```cpp
System::SharedPtr<IChartDataWorksheetCollection> Aspose::Slides::Charts::ChartDataWorkbook::get_Worksheets() override
```

## Poznámky


Příklad: 
```cpp
auto pres = System::MakeObject<Presentation>();

auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Pie, 50.0f, 50.0f, 400.0f, 500.0f);
auto workbook = chart->get_ChartData()->get_ChartDataWorkbook();
for (const auto& worksheet : workbook->get_Worksheets())
{
    System::String worksheetName = worksheet->get_Name();
}
```




## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IChartDataWorksheetCollection](../../ichartdataworksheetcollection/)
* Třída [ChartDataWorkbook](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)
---
title: get_Worksheets()
second_title: Aspose.Slides pro C++ API Reference
description: Získá kolekci pracovních listů.
type: docs
weight: 1
url: /cs/aspose.slides.charts/ichartdataworkbook/get_worksheets/
---
## IChartDataWorkbook::get_Worksheets() method


Získá kolekci pracovních listů.

```cpp
virtual System::SharedPtr<IChartDataWorksheetCollection> Aspose::Slides::Charts::IChartDataWorkbook::get_Worksheets()=0
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

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [IChartDataWorksheetCollection](../../ichartdataworksheetcollection/)
* Třída [IChartDataWorkbook](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)
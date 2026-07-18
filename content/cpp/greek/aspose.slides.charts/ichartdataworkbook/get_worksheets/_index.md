---
title: get_Worksheets()
second_title: Aspose.Slides για C++ Αναφορά API
description: Λαμβάνει μια συλλογή από φύλλα εργασίας.
type: docs
weight: 1
url: /el/aspose.slides.charts/ichartdataworkbook/get_worksheets/
---
## IChartDataWorkbook::get_Worksheets() μέθοδος


Λαμβάνει μια συλλογή από φύλλα εργασίας.

```cpp
virtual System::SharedPtr<IChartDataWorksheetCollection> Aspose::Slides::Charts::IChartDataWorkbook::get_Worksheets()=0
```

## Παρατηρήσεις


Παράδειγμα:
```cpp
auto pres = System::MakeObject<Presentation>();

auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Pie, 50.0f, 50.0f, 400.0f, 500.0f);
auto workbook = chart->get_ChartData()->get_ChartDataWorkbook();
for (const auto& worksheet : workbook->get_Worksheets())
{
    System::String worksheetName = worksheet->get_Name();
}
```




## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IChartDataWorksheetCollection](../../ichartdataworksheetcollection/)
* Κλάση [IChartDataWorkbook](../)
* Χώρος ονομάτων [Aspose::Slides::Charts](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
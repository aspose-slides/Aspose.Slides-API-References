---
title: get_Worksheets()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar en samling kalkylblad.
type: docs
weight: 1
url: /sv/aspose.slides.charts/ichartdataworkbook/get_worksheets/
---
## IChartDataWorkbook::get_Worksheets() metod

Hämtar en samling kalkylblad.

```cpp
virtual System::SharedPtr<IChartDataWorksheetCollection> Aspose::Slides::Charts::IChartDataWorkbook::get_Worksheets()=0
```

## Anmärkningar

Exempel:
```cpp
auto pres = System::MakeObject<Presentation>();

auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Pie, 50.0f, 50.0f, 400.0f, 500.0f);
auto workbook = chart->get_ChartData()->get_ChartDataWorkbook();
for (const auto& worksheet : workbook->get_Worksheets())
{
    System::String worksheetName = worksheet->get_Name();
}
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IChartDataWorksheetCollection](../../ichartdataworksheetcollection/)
* Klass [IChartDataWorkbook](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)
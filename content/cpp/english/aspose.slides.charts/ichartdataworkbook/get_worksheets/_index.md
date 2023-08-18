---
title: get_Worksheets()
second_title: Aspose.Slides for C++ API Reference
description: Gets a collection of worksheets.
type: docs
weight: 1
url: /aspose.slides.charts/ichartdataworkbook/get_worksheets/
---
## IChartDataWorkbook::get_Worksheets() method


Gets a collection of worksheets.

```cpp
virtual System::SharedPtr<IChartDataWorksheetCollection> Aspose::Slides::Charts::IChartDataWorkbook::get_Worksheets()=0
```

## Remarks


Example: 
```cpp
auto pres = System::MakeObject<Presentation>();

auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Pie, 50.0f, 50.0f, 400.0f, 500.0f);
auto workbook = chart->get_ChartData()->get_ChartDataWorkbook();
for (const auto& worksheet : workbook->get_Worksheets())
{
    System::String worksheetName = worksheet->get_Name();
}
```




## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartDataWorksheetCollection](../../ichartdataworksheetcollection/)
* Class [IChartDataWorkbook](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
---
title: get_Worksheets()
second_title: مرجع API Aspose.Slides للغة C++
description: يحصل على مجموعة من أوراق العمل.
type: docs
weight: 1
url: /ar/aspose.slides.charts/chartdataworkbook/get_worksheets/
---
## ChartDataWorkbook::get_Worksheets() طريقة


يحصل على مجموعة من أوراق العمل.

```cpp
System::SharedPtr<IChartDataWorksheetCollection> Aspose::Slides::Charts::ChartDataWorkbook::get_Worksheets() override
```

## ملاحظات


مثال: 
```cpp
auto pres = System::MakeObject<Presentation>();

auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Pie, 50.0f, 50.0f, 400.0f, 500.0f);
auto workbook = chart->get_ChartData()->get_ChartDataWorkbook();
for (const auto& worksheet : workbook->get_Worksheets())
{
    System::String worksheetName = worksheet->get_Name();
}
```




## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IChartDataWorksheetCollection](../../ichartdataworksheetcollection/)
* فئة [ChartDataWorkbook](../)
* نطاق [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
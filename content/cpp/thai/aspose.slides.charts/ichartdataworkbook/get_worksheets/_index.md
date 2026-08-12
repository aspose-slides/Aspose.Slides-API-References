---
title: get_Worksheets()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: รับคอลเลกชันของเวิร์กชีต.
type: docs
weight: 1
url: /th/aspose.slides.charts/ichartdataworkbook/get_worksheets/
---
## IChartDataWorkbook::get_Worksheets() วิธีการ


รับคอลเลกชันของเวิร์กชีต.

```cpp
virtual System::SharedPtr<IChartDataWorksheetCollection> Aspose::Slides::Charts::IChartDataWorkbook::get_Worksheets()=0
```

## หมายเหตุ


ตัวอย่าง:
```cpp
auto pres = System::MakeObject<Presentation>();

auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Pie, 50.0f, 50.0f, 400.0f, 500.0f);
auto workbook = chart->get_ChartData()->get_ChartDataWorkbook();
for (const auto& worksheet : workbook->get_Worksheets())
{
    System::String worksheetName = worksheet->get_Name();
}
```




## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IChartDataWorksheetCollection](../../ichartdataworksheetcollection/)
* คลาส [IChartDataWorkbook](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)
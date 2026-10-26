---
title: get_Worksheets()
second_title: Aspose.Slides for C++ API 參考
description: 取得工作表的集合。
type: docs
weight: 1
url: /zh-hant/aspose.slides.charts/chartdataworkbook/get_worksheets/
---
## ChartDataWorkbook::get_Worksheets() 方法


取得工作表的集合。

```cpp
System::SharedPtr<IChartDataWorksheetCollection> Aspose::Slides::Charts::ChartDataWorkbook::get_Worksheets() override
```

## 備註


範例： 
```cpp
auto pres = System::MakeObject<Presentation>();

auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Pie, 50.0f, 50.0f, 400.0f, 500.0f);
auto workbook = chart->get_ChartData()->get_ChartDataWorkbook();
for (const auto& worksheet : workbook->get_Worksheets())
{
    System::String worksheetName = worksheet->get_Name();
}
```




## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IChartDataWorksheetCollection](../../ichartdataworksheetcollection/)
* 類別 [ChartDataWorkbook](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)
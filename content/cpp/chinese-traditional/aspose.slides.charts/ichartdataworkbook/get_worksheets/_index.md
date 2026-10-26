---
title: get_Worksheets()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得 worksheets 集合。
type: docs
weight: 1
url: /zh-hant/aspose.slides.charts/ichartdataworkbook/get_worksheets/
---
## IChartDataWorkbook::get_Worksheets() 方法

取得 worksheets 集合。

```cpp
virtual System::SharedPtr<IChartDataWorksheetCollection> Aspose::Slides::Charts::IChartDataWorkbook::get_Worksheets()=0
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
* 類別 [IChartDataWorkbook](../)
* 名稱空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)
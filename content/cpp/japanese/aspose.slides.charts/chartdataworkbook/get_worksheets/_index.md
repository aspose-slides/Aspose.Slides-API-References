---
title: get_Worksheets()
second_title: Aspose.Slides for C++ API リファレンス
description: ワークシートのコレクションを取得します。
type: docs
weight: 1
url: /ja/aspose.slides.charts/chartdataworkbook/get_worksheets/
---
## ChartDataWorkbook::get_Worksheets() メソッド


ワークシートのコレクションを取得します。

```cpp
System::SharedPtr<IChartDataWorksheetCollection> Aspose::Slides::Charts::ChartDataWorkbook::get_Worksheets() override
```

## 備考


例: 
```cpp
auto pres = System::MakeObject<Presentation>();

auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Pie, 50.0f, 50.0f, 400.0f, 500.0f);
auto workbook = chart->get_ChartData()->get_ChartDataWorkbook();
for (const auto& worksheet : workbook->get_Worksheets())
{
    System::String worksheetName = worksheet->get_Name();
}
```




## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IChartDataWorksheetCollection](../../ichartdataworksheetcollection/)
* クラス [ChartDataWorkbook](../)
* 名前空間 [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
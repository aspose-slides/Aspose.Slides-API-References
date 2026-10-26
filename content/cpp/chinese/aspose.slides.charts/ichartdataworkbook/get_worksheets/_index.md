---
title: get_Worksheets()
second_title: Aspose.Slides for C++ API 参考
description: 获取 Worksheets 的集合。
type: docs
weight: 1
url: /zh/aspose.slides.charts/ichartdataworkbook/get_worksheets/
---
## IChartDataWorkbook::get_Worksheets() 方法


获取 Worksheets 的集合。

```cpp
virtual System::SharedPtr<IChartDataWorksheetCollection> Aspose::Slides::Charts::IChartDataWorkbook::get_Worksheets()=0
```

## 备注


示例： 
```cpp
auto pres = System::MakeObject<Presentation>();

auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Pie, 50.0f, 50.0f, 400.0f, 500.0f);
auto workbook = chart->get_ChartData()->get_ChartDataWorkbook();
for (const auto& worksheet : workbook->get_Worksheets())
{
    System::String worksheetName = worksheet->get_Name();
}
```




## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IChartDataWorksheetCollection](../../ichartdataworksheetcollection/)
* 类 [IChartDataWorkbook](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)
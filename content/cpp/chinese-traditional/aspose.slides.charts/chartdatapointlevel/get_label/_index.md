---
title: get_Label()
second_title: Aspose.Slides for C++ API 參考文件
description: 代表資料點層級的資料標籤。適用於 Treemap 和 Sunburst 系列類型。唯讀 IDataLabel.
type: docs
weight: 14
url: /zh-hant/aspose.slides.charts/chartdatapointlevel/get_label/
---
## ChartDataPointLevel::get_Label() 方法

代表資料點層級的資料標籤。適用於 Treemap 和 Sunburst 系列類型。唯讀 [IDataLabel](../../idatalabel/)。

```cpp
System::SharedPtr<IDataLabel> Aspose::Slides::Charts::ChartDataPointLevel::get_Label() override
```

## 備註



```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Sunburst, 50.0f, 50.0f, 500.0f, 400.0f);
auto series = chart->get_ChartData()->get_Series()->idx_get(0);
auto dataPointLevel = series->get_DataPoints()->idx_get(0)->get_DataPointLevels()->idx_get(1);

dataPointLevel->get_Label()->get_DataLabelFormat()->set_ShowCategoryName(false);
dataPointLevel->get_Label()->get_DataLabelFormat()->set_ShowValue(true);
dataPointLevel->get_Label()->get_DataLabelFormat()->set_ShowSeriesName(true);

dataPointLevel = series->get_DataPoints()->idx_get(12)->get_DataPointLevels()->idx_get(1);
dataPointLevel->get_Label()->get_TextFormat()->get_PortionFormat()->get_FillFormat()->set_FillType(FillType::Solid);
dataPointLevel->get_Label()->get_TextFormat()->get_PortionFormat()->get_FillFormat()->get_SolidFillColor()->set_Color(Color::get_Red());
```

## 參見

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IDataLabel](../../idatalabel/)
* 類別 [ChartDataPointLevel](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 程式庫 [Aspose.Slides](../../../)
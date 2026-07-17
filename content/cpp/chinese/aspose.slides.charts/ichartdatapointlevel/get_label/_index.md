---
title: get_Label()
second_title: Aspose.Slides C++ API 参考
description: 表示数据点级别的数据标签。适用于 Treemap 和 Sunburst 系列类型。只读 IDataLabel。
type: docs
weight: 14
url: /zh/aspose.slides.charts/ichartdatapointlevel/get_label/
---
## IChartDataPointLevel::get_Label() 方法


表示数据点级别的数据标签。适用于 Treemap 和 Sunburst 系列类型。只读 [IDataLabel](../../idatalabel/).

```cpp
virtual System::SharedPtr<IDataLabel> Aspose::Slides::Charts::IChartDataPointLevel::get_Label()=0
```

## 备注



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

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IDataLabel](../../idatalabel/)
* 类 [IChartDataPointLevel](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)
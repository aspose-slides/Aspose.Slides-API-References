---
title: get_Label()
second_title: Aspose.Slides for C++ API Reference
description: Represents data label of data point level. Applied for Treemap and Sunburst sereis types. Read-only IDataLabel.
type: docs
weight: 14
url: /cpp/aspose.slides.charts/ichartdatapointlevel/get_label/
---
## IChartDataPointLevel::get_Label() method


Represents data label of data point level. Applied for Treemap and Sunburst sereis types. Read-only [IDataLabel](../../idatalabel/).

```cpp
virtual System::SharedPtr<IDataLabel> Aspose::Slides::Charts::IChartDataPointLevel::get_Label()=0
```

## Remarks



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

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDataLabel](../../idatalabel/)
* Class [IChartDataPointLevel](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
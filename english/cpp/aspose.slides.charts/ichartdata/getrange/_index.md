---
title: GetRange()
second_title: Aspose.Slides for C++ API Reference
description: Gets chart data range.
type: docs
weight: 157
url: /cpp/aspose.slides.charts/ichartdata/getrange/
---
## IChartData::GetRange() method


Gets chart data range.

```cpp
virtual System::String Aspose::Slides::Charts::IChartData::GetRange()=0
```


### Return Value

Cells data range formula. E.g: \"Sheet1!$A$1:$C$4\"
## Remarks




```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 100.0f, 100.0f, 500.0f, 400.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## See Also

* Class [String](../../../system/string/)
* Class [IChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
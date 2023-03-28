---
title: GetRange()
second_title: Aspose.Slides for C++ API Reference
description: Gets chart data range.
type: docs
weight: 144
url: /cpp/aspose.slides.charts/chartdata/getrange/
---
## ChartData::GetRange() method


Gets chart data range.

```cpp
System::String Aspose::Slides::Charts::ChartData::GetRange() override
```


### Return Value

Cells data range formula. E.g: \"Sheet1!$A$1:$C$4\"
## Remarks




```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 0.0f, 0.0f, 100.0f, 100.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## See Also

* Class [String](../../../system/string/)
* Class [ChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)

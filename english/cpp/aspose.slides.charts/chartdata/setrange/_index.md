---
title: SetRange()
second_title: Aspose.Slides for C++ API Reference
description: Set chart data range. Series and categories will be updated based on new data range. If amount of series in data range greater than count of series in the chart data then additional series with the same type as a last series in the current collection will be added to the end of the collection.
type: docs
weight: 157
url: /cpp/aspose.slides.charts/chartdata/setrange/
---
## ChartData::SetRange([System::String](../../../system/string/)) method


Set chart data range. Series and categories will be updated based on new data range. If amount of series in data range greater than count of series in the chart data then additional series with the same type as a last series in the current collection will be added to the end of the collection.

```cpp
void Aspose::Slides::Charts::ChartData::SetRange(System::String formula) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | The cells data range formula. E.g: \"Sheet1!$A$1:$C$4\" , \"SomeSheetName!A1:B100\", \"Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5\". |

## See Also

* Class [String](../../../system/string/)
* Class [ChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)

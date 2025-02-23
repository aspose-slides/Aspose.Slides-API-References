---
title: GetRange
second_title: Aspose.Sildes for .NET API Reference
description: Gets chart data range.
type: docs
weight: 90
url: /aspose.slides.charts/ichartdata/getrange/
---

## IChartData.GetRange method

Gets chart data range.

```csharp
public string GetRange()
```

### Return Value

Cells data range formula. E.g: "Sheet1!$A$1:$C$4"

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Chart doesn't use workbook as a data source |

### Examples

Example C#

```csharp
using (Presentation pres = new Presentation())
{
    IChart chart = pres.Slides[0].Shapes.AddChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
    string result = (chart.ChartData as ChartData).GetRange();
}
```

### See Also

* interface [IChartData](../../ichartdata)
* namespace [Aspose.Slides.Charts](../../ichartdata)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->

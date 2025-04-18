---
title: RecoverWorkbookFromChartCache
second_title: Aspose.Sildes for .NET API Reference
description: If data source for the chart is an external workbook and its not available it will be recovered from the chart cache.
type: docs
weight: 30
url: /aspose.slides/spreadsheetoptions/recoverworkbookfromchartcache/
---

## SpreadsheetOptions.RecoverWorkbookFromChartCache property

If data source for the chart is an external workbook and it's not available, it will be recovered from the chart cache.

```csharp
public bool RecoverWorkbookFromChartCache { get; set; }
```

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Thrown when external workbook in unavailable and RecoverWorkbookFromChartCache property value is false. |

### Examples

Example:

```csharp
[C#]
LoadOptions loadOptions = new LoadOptions
{
    SpreadsheetOptions = new SpreadsheetOptions
    {
        RecoverWorkbookFromChartCache = true
    }
};

using (Presentation pres = new Presentation("Presentation.pptx", loadOptions))
{
    IChart chart = pres.Slides[0].Shapes[0] as IChart;
    IChartDataWorkbook recoveredWorkbook = chart.ChartData.ChartDataWorkbook;
}
```

### See Also

* class [SpreadsheetOptions](../../spreadsheetoptions)
* namespace [Aspose.Slides](../../spreadsheetoptions)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->

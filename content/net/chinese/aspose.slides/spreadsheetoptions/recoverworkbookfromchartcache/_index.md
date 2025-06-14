---
title: RecoverWorkbookFromChartCache
second_title: Aspose.Sildes for .NET API Reference
description: 如果图表的数据源是外部工作簿并且不可用，它将从图表缓存中恢复。
type: docs
weight: 30
url: /zh/aspose.slides/spreadsheetoptions/recoverworkbookfromchartcache/
---

## SpreadsheetOptions.RecoverWorkbookFromChartCache 属性

如果图表的数据源是外部工作簿并且不可用，它将从图表缓存中恢复。

```csharp
public bool RecoverWorkbookFromChartCache { get; set; }
```

### 异常

| exception | condition |
| --- | --- |
| InvalidOperationException | 当外部工作簿不可用且 RecoverWorkbookFromChartCache 属性值为 false 时抛出。 |

### 示例

示例：

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

### 另见

* class [SpreadsheetOptions](../../spreadsheetoptions)
* namespace [Aspose.Slides](../../spreadsheetoptions)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
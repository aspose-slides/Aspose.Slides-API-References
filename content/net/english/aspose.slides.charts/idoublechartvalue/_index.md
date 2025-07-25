---
title: IDoubleChartValue
second_title: Aspose.Sildes for .NET API Reference
description: Represent double value which can be stored in pptx presentation document in two ways 1 in cell/cells of workbook related to chart 2 as literal value.
type: docs
weight: 2050
url: /aspose.slides.charts/idoublechartvalue/
---

## IDoubleChartValue interface

Represent double value which can be stored in pptx presentation document in two ways: 1) in cell/cells of workbook related to chart; 2) as literal value.

```csharp
public interface IDoubleChartValue : ISingleCellChartValue
```

## Properties

| Name | Description |
| --- | --- |
| [AsISingleCellChartValue](../../aspose.slides.charts/idoublechartvalue/asisinglecellchartvalue) { get; } | Allows to get base ISingleCellChartValue interface. Read-only [`ISingleCellChartValue`](../isinglecellchartvalue). |
| [AsLiteralDouble](../../aspose.slides.charts/idoublechartvalue/asliteraldouble) { get; set; } | Returns or sets literal double value if DataSourceType = Charts.DataSourceType.DoubleLiterals. Read/write Double. |

## Methods

| Name | Description |
| --- | --- |
| [ToDouble](../../aspose.slides.charts/idoublechartvalue/todouble)() | Converst to double. |

### See Also

* interface [ISingleCellChartValue](../isinglecellchartvalue)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->

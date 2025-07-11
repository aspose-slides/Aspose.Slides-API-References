---
title: IChartDataCell
second_title: Aspose.Sildes for .NET API Reference
description: Represents cell for chart data.
type: docs
weight: 1790
url: /aspose.slides.charts/ichartdatacell/
---

## IChartDataCell interface

Represents cell for chart data.

```csharp
public interface IChartDataCell
```

## Properties

| Name | Description |
| --- | --- |
| [ChartDataWorksheet](../../aspose.slides.charts/ichartdatacell/chartdataworksheet) { get; } | Gets the worksheet. Read-only [`IChartDataWorksheet`](../ichartdataworksheet). |
| [Column](../../aspose.slides.charts/ichartdatacell/column) { get; } | Returns the index of the column of worksheet in which the cell is located. Read-only Int32. |
| [CustomNumberFormat](../../aspose.slides.charts/ichartdatacell/customnumberformat) { get; set; } | Gets or sets the custom display format of numbers and dates. If value is empty will be used PresetNumberFormat value. Read/write String. |
| [Formula](../../aspose.slides.charts/ichartdatacell/formula) { get; set; } | Gets or sets the formula in A1-style. |
| [IsHidden](../../aspose.slides.charts/ichartdatacell/ishidden) { get; } | Determines whether the cell is hidden. Read-only Boolean. |
| [PresetNumberFormat](../../aspose.slides.charts/ichartdatacell/presetnumberformat) { get; set; } | Gets or sets the built-in display format of numbers and dates. Preset number must be in [0..22] or [37..49]. Read/write Byte. |
| [R1C1Formula](../../aspose.slides.charts/ichartdatacell/r1c1formula) { get; set; } | Gets or sets the formula in R1C1-style. |
| [Row](../../aspose.slides.charts/ichartdatacell/row) { get; } | Returns the index of the row of worksheet in which the cell is located. Read-only Int32. |
| [Value](../../aspose.slides.charts/ichartdatacell/value) { get; set; } | Gets or sets the value of a cell. Read/write Object. |

## Methods

| Name | Description |
| --- | --- |
| [Calculate](../../aspose.slides.charts/ichartdatacell/calculate)(bool) | If the cell contains a formula, the value will be updated base on that formula. |

### See Also

* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->

---
title: ITrendline
second_title: Aspose.Sildes for .NET API Reference
description: Class represents trend line of chart series
type: docs
weight: 2220
url: /aspose.slides.charts/itrendline/
---

## ITrendline interface

Class represents trend line of chart series

```csharp
public interface ITrendline : IOverridableText
```

## Properties

| Name | Description |
| --- | --- |
| [AsIOverridableText](../../aspose.slides.charts/itrendline/asioverridabletext) { get; } | Returns IOverridableText interface. Read-only [`IOverridableText`](../ioverridabletext). |
| [Backward](../../aspose.slides.charts/itrendline/backward) { get; set; } | Specifies the number of categories (or units on a scatter chart) that the trend line extends before the data for the series that is being trended. On scatter and non-scatter charts, the value shall be any nonnegative value. Read/write Double. |
| [DisplayEquation](../../aspose.slides.charts/itrendline/displayequation) { get; set; } | Specifies that the equation for the trendline is displayed on the chart (in the same label as the Rsquaredvalue). Read/write Boolean. |
| [DisplayRSquaredValue](../../aspose.slides.charts/itrendline/displayrsquaredvalue) { get; set; } | Specifies that the R-squared value of the trendline is displayed on the chart (in the same label as the equation). Read/write Boolean. |
| [Format](../../aspose.slides.charts/itrendline/format) { get; set; } | Represents the format of the trend line. Read/write [`IFormat`](../iformat). |
| [Forward](../../aspose.slides.charts/itrendline/forward) { get; set; } | Specifies the number of categories (or units on a scatter chart) that the trendline extends after the data for the series that is being trended. On scatter and non-scatter charts, the value shall be any non-negative value. Read/write Double. |
| [Intercept](../../aspose.slides.charts/itrendline/intercept) { get; set; } | Specifies the value where the trendline shall cross the y axis. This property shall be supported only when the trendline type is exp, linear, or poly. Read/write Double. |
| [Order](../../aspose.slides.charts/itrendline/order) { get; set; } | Specifies the order of the polynomial trend line. It is ignored for other trend line types. Value must be between 2 and 6. Read/write Byte. |
| [Period](../../aspose.slides.charts/itrendline/period) { get; set; } | Specifies the period of the trend line for a moving average trend line. It is ignored for other trend line variants. Value must be between 2 and 255. Read/write Byte. |
| [RelatedLegendEntry](../../aspose.slides.charts/itrendline/relatedlegendentry) { get; } | Represents legend entry related with this trendline Read-only [`ILegendEntryProperties`](../ilegendentryproperties). |
| [TrendlineName](../../aspose.slides.charts/itrendline/trendlinename) { get; set; } | Gets or sets name of the trendline. Read/write String. |
| [TrendlineType](../../aspose.slides.charts/itrendline/trendlinetype) { get; set; } | Gets or sets type of trend line. Read/write [`TrendlineType`](./trendlinetype). |

### See Also

* interface [IOverridableText](../ioverridabletext)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->

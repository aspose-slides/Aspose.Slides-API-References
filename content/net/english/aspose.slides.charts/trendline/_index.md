---
title: Trendline
second_title: Aspose.Sildes for .NET API Reference
description: Class represents trend line of chart series
type: docs
weight: 2450
url: /aspose.slides.charts/trendline/
---

## Trendline class

Class represents trend line of chart series

```csharp
public class Trendline : DomObject<TrendlineCollection>, ITrendline
```

## Properties

| Name | Description |
| --- | --- |
| [Backward](../../aspose.slides.charts/trendline/backward) { get; set; } | Specifies the number of categories (or units on a scatter chart) that the trend line extends before the data for the series that is being trended. On scatter and non-scatter charts, the value shall be any nonnegative value. Read/write Double. |
| [Chart](../../aspose.slides.charts/trendline/chart) { get; } | Returns the parent chart. Read-only [`IChart`](../ichart). |
| [DisplayEquation](../../aspose.slides.charts/trendline/displayequation) { get; set; } | Specifies that the equation for the trendline is displayed on the chart (in the same label as the Rsquaredvalue). Read/write Boolean. |
| [DisplayRSquaredValue](../../aspose.slides.charts/trendline/displayrsquaredvalue) { get; set; } | Specifies that the R-squared value of the trendline is displayed on the chart (in the same label as the equation). Read/write Boolean. |
| [Format](../../aspose.slides.charts/trendline/format) { get; set; } | Represents the format of the trend line. Read/write [`IFormat`](../iformat). |
| [Forward](../../aspose.slides.charts/trendline/forward) { get; set; } | Specifies the number of categories (or units on a scatter chart) that the trendline extends after the data for the series that is being trended. On scatter and non-scatter charts, the value shall be any non-negative value. Read/write Double. |
| [Intercept](../../aspose.slides.charts/trendline/intercept) { get; set; } | Specifies the value where the trendline shall cross the y axis. This property shall be supported only when the trendline type is exp, linear, or poly. Read/write Double. |
| [Order](../../aspose.slides.charts/trendline/order) { get; set; } | Specifies the order of the polynomial trend line. It is ignored for other trend line types. Value must be between 2 and 6. Read/write Byte. |
| [Period](../../aspose.slides.charts/trendline/period) { get; set; } | Specifies the period of the trend line for a moving average trend line. It is ignored for other trend line variants. Value must be between 2 and 255. Read/write Byte. |
| [RelatedLegendEntry](../../aspose.slides.charts/trendline/relatedlegendentry) { get; } | Represents legend entry related with this trendline Read-only [`ILegendEntryProperties`](../ilegendentryproperties). |
| [TextFormat](../../aspose.slides.charts/trendline/textformat) { get; } | Returns text format. Read-only [`IChartTextFormat`](../icharttextformat). |
| [TextFrameForOverriding](../../aspose.slides.charts/trendline/textframeforoverriding) { get; } | Can contain a rich formatted text. If this property is not null then this formatted text value overrides auto-generated text of data label. Auto-generated text of data label means text that is managed by ShowSeriesName, ShowValue, ... properties and is formatted with the TextFormatManager.TextFormat property. Read-only [`ITextFrame`](../../aspose.slides/itextframe). |
| [TrendlineName](../../aspose.slides.charts/trendline/trendlinename) { get; set; } | Gets or sets name of the trendline. Read/write String. |
| [TrendlineType](../../aspose.slides.charts/trendline/trendlinetype) { get; set; } | Gets or sets type of trend line. Read/write [`TrendlineType`](../trendlinetype). |

## Methods

| Name | Description |
| --- | --- |
| [AddTextFrameForOverriding](../../aspose.slides.charts/trendline/addtextframeforoverriding)(string) | Initialize TextFrameForOverriding with the text in paramener "text". If TextFrameForOverriding is already initialized then simply changes its text. |

### See Also

* class [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* class [TrendlineCollection](../trendlinecollection)
* interface [ITrendline](../itrendline)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->

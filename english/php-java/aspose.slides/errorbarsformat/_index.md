---
title: ErrorBarsFormat
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/aspose.slides/errorbarsformat/
---

## ErrorBarsFormat class

 Represents error bars of chart series. ErrorBars custom values are in IChartDataPointCollection
 (in ( IChartDataPoint#getErrorBarsCustomValues) property).
 

## Methods

| Name | Description |
| --- | --- |
| [getChart](getchart)() | Returns the parent chart. Read-only IChart. |
| [getFormat](getformat)() | Represents the format of the error bars. Read/write IFormat. |
| [getPresentation](getpresentation)() | Returns the parent presentation of a FillFormat. Read-only IPresentation. |
| [getSlide](getslide)() | Returns the parent slide of a FillFormat. Read-only BaseSlide. |
| [getType](gettype)() | Gets or sets type of error bars. Read/write ErrorBarType. |
| [getValue](getvalue)() | Gets or sets value which is used with Fixed, Percentage and StandardDeviation value types to determine the length of the error bars. In any other case will return NaN. Read/write float. |
| [getValueType](getvaluetype)() | Represents possible ways to determine the length of the error bars. In case of custom value type to specify value use ( IChartDataPoint#getErrorBarsCustomValues) property of specific data point in DataPoints collection of series. In case of Fixed, Percentage or StandardDeviation value type use Value property to specify value. Read/write ErrorBarValueType. |
| [hasEndCap](hasendcap)() | Specifies an end cap is not drawn on the error bars. Read/write boolean. |
| [isVisible](isvisible)() | Gets or sets Error Bars visibility . Read/write boolean. |
| [setEndCap](setendcap)(boolean) | Specifies an end cap is not drawn on the error bars. Read/write boolean. |
| [setFormat](setformat)([Format](../format)) | Represents the format of the error bars. Read/write IFormat. |
| [setType](settype)(int) | Gets or sets type of error bars. Read/write ErrorBarType. |
| [setValue](setvalue)(float) | Gets or sets value which is used with Fixed, Percentage and StandardDeviation value types to determine the length of the error bars. In any other case will return NaN. Read/write float. |
| [setValueType](setvaluetype)(int) | Represents possible ways to determine the length of the error bars. In case of custom value type to specify value use ( IChartDataPoint#getErrorBarsCustomValues) property of specific data point in DataPoints collection of series. In case of Fixed, Percentage or StandardDeviation value type use Value property to specify value. Read/write ErrorBarValueType. |
| [setVisible](setvisible)(boolean) | Gets or sets Error Bars visibility . Read/write boolean. |

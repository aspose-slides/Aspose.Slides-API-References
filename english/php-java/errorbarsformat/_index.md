---
title: ErrorBarsFormat
type: docs
weight: 0
url: /php-java/errorbarsformat/
---

# ErrorBarsFormat class

 Represents error bars of chart series. ErrorBars custom values are in IChartDataPointCollection
 (in ( IChartDataPoint#getErrorBarsCustomValues) property).
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [getChart](/php-java/errorbarsformat/getchart/)() | IChart | Returns the parent chart. Read-only IChart. |
| [getFormat](/php-java/errorbarsformat/getformat/)() | IFormat | Represents the format of the error bars. Read/write IFormat. |
| [getPresentation](/php-java/errorbarsformat/getpresentation/)() | IPresentation | Returns the parent presentation of a FillFormat. Read-only IPresentation. |
| [getSlide](/php-java/errorbarsformat/getslide/)() | IBaseSlide | Returns the parent slide of a FillFormat. Read-only BaseSlide. |
| [getType](/php-java/errorbarsformat/gettype/)() | int | Gets or sets type of error bars. Read/write ErrorBarType. |
| [getValue](/php-java/errorbarsformat/getvalue/)() | float | Gets or sets value which is used with Fixed, Percentage and StandardDeviation value types to determine the length of the error bars. In any other case will return NaN. Read/write float. |
| [getValueType](/php-java/errorbarsformat/getvaluetype/)() | int | Represents possible ways to determine the length of the error bars. In case of custom value type to specify value use ( IChartDataPoint#getErrorBarsCustomValues) property of specific data point in DataPoints collection of series. In case of Fixed, Percentage or StandardDeviation value type use Value property to specify value. Read/write ErrorBarValueType. |
| [hasEndCap](/php-java/errorbarsformat/hasendcap/)() | boolean | Specifies an end cap is not drawn on the error bars. Read/write boolean. |
| [isVisible](/php-java/errorbarsformat/isvisible/)() | boolean | Gets or sets Error Bars visibility . Read/write boolean. |
| [setEndCap](/php-java/errorbarsformat/setendcap/)(boolean) | void | Specifies an end cap is not drawn on the error bars. Read/write boolean. |
| [setFormat](/php-java/errorbarsformat/setformat/)(IFormat) | void | Represents the format of the error bars. Read/write IFormat. |
| [setType](/php-java/errorbarsformat/settype/)(int) | void | Gets or sets type of error bars. Read/write ErrorBarType. |
| [setValue](/php-java/errorbarsformat/setvalue/)(float) | void | Gets or sets value which is used with Fixed, Percentage and StandardDeviation value types to determine the length of the error bars. In any other case will return NaN. Read/write float. |
| [setValueType](/php-java/errorbarsformat/setvaluetype/)(int) | void | Represents possible ways to determine the length of the error bars. In case of custom value type to specify value use ( IChartDataPoint#getErrorBarsCustomValues) property of specific data point in DataPoints collection of series. In case of Fixed, Percentage or StandardDeviation value type use Value property to specify value. Read/write ErrorBarValueType. |
| [setVisible](/php-java/errorbarsformat/setvisible/)(boolean) | void | Gets or sets Error Bars visibility . Read/write boolean. |

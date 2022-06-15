---
title: Trendline
type: docs
weight: 0
url: /php-java/trendline/
---

# Trendline class

 Class represents trend line of chart series
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [addTextFrameForOverriding](/slides/php-java/trendline/addtextframeforoverriding/)(String) | ITextFrame | Initialize TextFrameForOverriding with the text in paramener "text". If TextFrameForOverriding is already initialized then simply changes its text. |
| [getBackward](/slides/php-java/trendline/getbackward/)() | double | Specifies the number of categories (or units on a scatter chart) that the trend line extends before the data for the series that is being trended. On scatter and non-scatter charts, the value shall be any nonnegative value. Read/write double. |
| [getChart](/slides/php-java/trendline/getchart/)() | IChart | Returns the parent chart. Read-only IChart. |
| [getDisplayEquation](/slides/php-java/trendline/getdisplayequation/)() | boolean | Specifies that the equation for the trendline is displayed on the chart (in the same label as the Rsquaredvalue). Read/write boolean. |
| [getDisplayRSquaredValue](/slides/php-java/trendline/getdisplayrsquaredvalue/)() | boolean | Specifies that the R-squared value of the trendline is displayed on the chart (in the same label as the equation). Read/write boolean. |
| [getFormat](/slides/php-java/trendline/getformat/)() | IFormat | Represents the format of the trend line. Read/write IFormat. |
| [getForward](/slides/php-java/trendline/getforward/)() | double | Specifies the number of categories (or units on a scatter chart) that the trendline extends after the data for the series that is being trended. On scatter and non-scatter charts, the value shall be any non-negative value. Read/write double. |
| [getIntercept](/slides/php-java/trendline/getintercept/)() | double | Specifies the value where the trendline shall cross the y axis. This property shall be supported only when the trendline type is exp, linear, or poly. Read/write double. |
| [getOrder](/slides/php-java/trendline/getorder/)() | byte | Specifies the order of the polynomial trend line. It is ignored for other trend line types. Value must be between 2 and 6. Read/write byte. |
| [getPeriod](/slides/php-java/trendline/getperiod/)() | byte | Specifies the period of the trend line for a moving average trend line. It is ignored for other trend line variants. Value must be between 2 and 255. Read/write byte. |
| [getPresentation](/slides/php-java/trendline/getpresentation/)() | IPresentation | Returns the parent presentation of a FillFormat. Read-only IPresentation. |
| [getRelatedLegendEntry](/slides/php-java/trendline/getrelatedlegendentry/)() | ILegendEntryProperties | Represents legend entry related with this trendline Read-only ILegendEntryProperties. |
| [getSlide](/slides/php-java/trendline/getslide/)() | IBaseSlide | Returns the parent slide of a FillFormat. Read-only BaseSlide. |
| [getTextFormat](/slides/php-java/trendline/gettextformat/)() | IChartTextFormat | Returns text format. Read-only IChartTextFormat. |
| [getTextFrameForOverriding](/slides/php-java/trendline/gettextframeforoverriding/)() | ITextFrame | Can contain a rich formatted text. If this property is not null then this formatted text value overrides auto-generated text of data label. Auto-generated text of data label means text that is managed by ShowSeriesName, ShowValue, ... properties and is formatted with the TextFormatManager.TextFormat property. Read-only ITextFrame. |
| [getTrendlineName](/slides/php-java/trendline/gettrendlinename/)() | String | Gets or sets name of the trendline. Read/write String. |
| [getTrendlineType](/slides/php-java/trendline/gettrendlinetype/)() | int | Gets or sets type of trend line. Read/write TrendlineType. |
| [setBackward](/slides/php-java/trendline/setbackward/)(double) | void | Specifies the number of categories (or units on a scatter chart) that the trend line extends before the data for the series that is being trended. On scatter and non-scatter charts, the value shall be any nonnegative value. Read/write double. |
| [setDisplayEquation](/slides/php-java/trendline/setdisplayequation/)(boolean) | void | Specifies that the equation for the trendline is displayed on the chart (in the same label as the Rsquaredvalue). Read/write boolean. |
| [setDisplayRSquaredValue](/slides/php-java/trendline/setdisplayrsquaredvalue/)(boolean) | void | Specifies that the R-squared value of the trendline is displayed on the chart (in the same label as the equation). Read/write boolean. |
| [setFormat](/slides/php-java/trendline/setformat/)(IFormat) | void | Represents the format of the trend line. Read/write IFormat. |
| [setForward](/slides/php-java/trendline/setforward/)(double) | void | Specifies the number of categories (or units on a scatter chart) that the trendline extends after the data for the series that is being trended. On scatter and non-scatter charts, the value shall be any non-negative value. Read/write double. |
| [setIntercept](/slides/php-java/trendline/setintercept/)(double) | void | Specifies the value where the trendline shall cross the y axis. This property shall be supported only when the trendline type is exp, linear, or poly. Read/write double. |
| [setOrder](/slides/php-java/trendline/setorder/)(byte) | void | Specifies the order of the polynomial trend line. It is ignored for other trend line types. Value must be between 2 and 6. Read/write byte. |
| [setPeriod](/slides/php-java/trendline/setperiod/)(byte) | void | Specifies the period of the trend line for a moving average trend line. It is ignored for other trend line variants. Value must be between 2 and 255. Read/write byte. |
| [setTrendlineName](/slides/php-java/trendline/settrendlinename/)(String) | void | Gets or sets name of the trendline. Read/write String. |
| [setTrendlineType](/slides/php-java/trendline/settrendlinetype/)(int) | void | Gets or sets type of trend line. Read/write TrendlineType. |

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
| [addTextFrameForOverriding](/php-java/trendline/addtextframeforoverriding/)(String) | ITextFrame | Initialize TextFrameForOverriding with the text in paramener "text". If TextFrameForOverriding is already initialized then simply changes its text. |
| [getBackward](/php-java/trendline/getbackward/)() | double | Specifies the number of categories (or units on a scatter chart) that the trend line extends before the data for the series that is being trended. On scatter and non-scatter charts, the value shall be any nonnegative value. Read/write double. |
| [getChart](/php-java/trendline/getchart/)() | IChart | Returns the parent chart. Read-only IChart. |
| [getDisplayEquation](/php-java/trendline/getdisplayequation/)() | boolean | Specifies that the equation for the trendline is displayed on the chart (in the same label as the Rsquaredvalue). Read/write boolean. |
| [getDisplayRSquaredValue](/php-java/trendline/getdisplayrsquaredvalue/)() | boolean | Specifies that the R-squared value of the trendline is displayed on the chart (in the same label as the equation). Read/write boolean. |
| [getFormat](/php-java/trendline/getformat/)() | IFormat | Represents the format of the trend line. Read/write IFormat. |
| [getForward](/php-java/trendline/getforward/)() | double | Specifies the number of categories (or units on a scatter chart) that the trendline extends after the data for the series that is being trended. On scatter and non-scatter charts, the value shall be any non-negative value. Read/write double. |
| [getIntercept](/php-java/trendline/getintercept/)() | double | Specifies the value where the trendline shall cross the y axis. This property shall be supported only when the trendline type is exp, linear, or poly. Read/write double. |
| [getOrder](/php-java/trendline/getorder/)() | byte | Specifies the order of the polynomial trend line. It is ignored for other trend line types. Value must be between 2 and 6. Read/write byte. |
| [getPeriod](/php-java/trendline/getperiod/)() | byte | Specifies the period of the trend line for a moving average trend line. It is ignored for other trend line variants. Value must be between 2 and 255. Read/write byte. |
| [getPresentation](/php-java/trendline/getpresentation/)() | IPresentation | Returns the parent presentation of a FillFormat. Read-only IPresentation. |
| [getRelatedLegendEntry](/php-java/trendline/getrelatedlegendentry/)() | ILegendEntryProperties | Represents legend entry related with this trendline Read-only ILegendEntryProperties. |
| [getSlide](/php-java/trendline/getslide/)() | IBaseSlide | Returns the parent slide of a FillFormat. Read-only BaseSlide. |
| [getTextFormat](/php-java/trendline/gettextformat/)() | IChartTextFormat | Returns text format. Read-only IChartTextFormat. |
| [getTextFrameForOverriding](/php-java/trendline/gettextframeforoverriding/)() | ITextFrame | Can contain a rich formatted text. If this property is not null then this formatted text value overrides auto-generated text of data label. Auto-generated text of data label means text that is managed by ShowSeriesName, ShowValue, ... properties and is formatted with the TextFormatManager.TextFormat property. Read-only ITextFrame. |
| [getTrendlineName](/php-java/trendline/gettrendlinename/)() | String | Gets or sets name of the trendline. Read/write String. |
| [getTrendlineType](/php-java/trendline/gettrendlinetype/)() | int | Gets or sets type of trend line. Read/write TrendlineType. |
| [setBackward](/php-java/trendline/setbackward/)(double) | void | Specifies the number of categories (or units on a scatter chart) that the trend line extends before the data for the series that is being trended. On scatter and non-scatter charts, the value shall be any nonnegative value. Read/write double. |
| [setDisplayEquation](/php-java/trendline/setdisplayequation/)(boolean) | void | Specifies that the equation for the trendline is displayed on the chart (in the same label as the Rsquaredvalue). Read/write boolean. |
| [setDisplayRSquaredValue](/php-java/trendline/setdisplayrsquaredvalue/)(boolean) | void | Specifies that the R-squared value of the trendline is displayed on the chart (in the same label as the equation). Read/write boolean. |
| [setFormat](/php-java/trendline/setformat/)(IFormat) | void | Represents the format of the trend line. Read/write IFormat. |
| [setForward](/php-java/trendline/setforward/)(double) | void | Specifies the number of categories (or units on a scatter chart) that the trendline extends after the data for the series that is being trended. On scatter and non-scatter charts, the value shall be any non-negative value. Read/write double. |
| [setIntercept](/php-java/trendline/setintercept/)(double) | void | Specifies the value where the trendline shall cross the y axis. This property shall be supported only when the trendline type is exp, linear, or poly. Read/write double. |
| [setOrder](/php-java/trendline/setorder/)(byte) | void | Specifies the order of the polynomial trend line. It is ignored for other trend line types. Value must be between 2 and 6. Read/write byte. |
| [setPeriod](/php-java/trendline/setperiod/)(byte) | void | Specifies the period of the trend line for a moving average trend line. It is ignored for other trend line variants. Value must be between 2 and 255. Read/write byte. |
| [setTrendlineName](/php-java/trendline/settrendlinename/)(String) | void | Gets or sets name of the trendline. Read/write String. |
| [setTrendlineType](/php-java/trendline/settrendlinetype/)(int) | void | Gets or sets type of trend line. Read/write TrendlineType. |

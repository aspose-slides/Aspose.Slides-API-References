---
title: Trendline
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/trendline/
---

## Trendline class

 Class represents trend line of chart series
 

## Functions

| Name | Description |
| --- | --- |
| [addTextFrameForOverriding](addtextframeforoverriding)(String) | Initialize TextFrameForOverriding with the text in paramener "text". If TextFrameForOverriding is already initialized then simply changes its text. |
| [getBackward](getbackward)() | Specifies the number of categories (or units on a scatter chart) that the trend line extends before the data for the series that is being trended. On scatter and non-scatter charts, the value shall be any nonnegative value. Read/write double. |
| [getChart](getchart)() | Returns the parent chart. Read-only IChart. |
| [getDisplayEquation](getdisplayequation)() | Specifies that the equation for the trendline is displayed on the chart (in the same label as the Rsquaredvalue). Read/write boolean. |
| [getDisplayRSquaredValue](getdisplayrsquaredvalue)() | Specifies that the R-squared value of the trendline is displayed on the chart (in the same label as the equation). Read/write boolean. |
| [getFormat](getformat)() | Represents the format of the trend line. Read/write IFormat. |
| [getForward](getforward)() | Specifies the number of categories (or units on a scatter chart) that the trendline extends after the data for the series that is being trended. On scatter and non-scatter charts, the value shall be any non-negative value. Read/write double. |
| [getIntercept](getintercept)() | Specifies the value where the trendline shall cross the y axis. This property shall be supported only when the trendline type is exp, linear, or poly. Read/write double. |
| [getOrder](getorder)() | Specifies the order of the polynomial trend line. It is ignored for other trend line types. Value must be between 2 and 6. Read/write byte. |
| [getPeriod](getperiod)() | Specifies the period of the trend line for a moving average trend line. It is ignored for other trend line variants. Value must be between 2 and 255. Read/write byte. |
| [getPresentation](getpresentation)() | Returns the parent presentation of a FillFormat. Read-only IPresentation. |
| [getRelatedLegendEntry](getrelatedlegendentry)() | Represents legend entry related with this trendline Read-only ILegendEntryProperties. |
| [getSlide](getslide)() | Returns the parent slide of a FillFormat. Read-only BaseSlide. |
| [getTextFormat](gettextformat)() | Returns text format. Read-only IChartTextFormat. |
| [getTextFrameForOverriding](gettextframeforoverriding)() | Can contain a rich formatted text. If this property is not null then this formatted text value overrides auto-generated text of data label. Auto-generated text of data label means text that is managed by ShowSeriesName, ShowValue, ... properties and is formatted with the TextFormatManager.TextFormat property. Read-only ITextFrame. |
| [getTrendlineName](gettrendlinename)() | Gets or sets name of the trendline. Read/write String. |
| [getTrendlineType](gettrendlinetype)() | Gets or sets type of trend line. Read/write TrendlineType. |
| [setBackward](setbackward)(double) | Specifies the number of categories (or units on a scatter chart) that the trend line extends before the data for the series that is being trended. On scatter and non-scatter charts, the value shall be any nonnegative value. Read/write double. |
| [setDisplayEquation](setdisplayequation)(boolean) | Specifies that the equation for the trendline is displayed on the chart (in the same label as the Rsquaredvalue). Read/write boolean. |
| [setDisplayRSquaredValue](setdisplayrsquaredvalue)(boolean) | Specifies that the R-squared value of the trendline is displayed on the chart (in the same label as the equation). Read/write boolean. |
| [setFormat](setformat)([Format](../format)) | Represents the format of the trend line. Read/write IFormat. |
| [setForward](setforward)(double) | Specifies the number of categories (or units on a scatter chart) that the trendline extends after the data for the series that is being trended. On scatter and non-scatter charts, the value shall be any non-negative value. Read/write double. |
| [setIntercept](setintercept)(double) | Specifies the value where the trendline shall cross the y axis. This property shall be supported only when the trendline type is exp, linear, or poly. Read/write double. |
| [setOrder](setorder)(byte) | Specifies the order of the polynomial trend line. It is ignored for other trend line types. Value must be between 2 and 6. Read/write byte. |
| [setPeriod](setperiod)(byte) | Specifies the period of the trend line for a moving average trend line. It is ignored for other trend line variants. Value must be between 2 and 255. Read/write byte. |
| [setTrendlineName](settrendlinename)(String) | Gets or sets name of the trendline. Read/write String. |
| [setTrendlineType](settrendlinetype)(int) | Gets or sets type of trend line. Read/write TrendlineType. |

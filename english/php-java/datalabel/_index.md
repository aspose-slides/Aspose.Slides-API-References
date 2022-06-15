---
title: DataLabel
type: docs
weight: 0
url: /php-java/datalabel/
---

# DataLabel class

 Represents a series labels.
 

## Constructors

| name | description |
| --- | --- |
| [DataLabel](/slides/php-java/datalabel/datalabel/)(IChartDataPoint) | Creates a new instance of DataLabel class. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [addTextFrameForOverriding](/slides/php-java/datalabel/addtextframeforoverriding/)(String) | ITextFrame | Initialize TextFrameForOverriding with the text in paramener "text". If TextFrameForOverriding is already initialized then simply changes its text. |
| [getActualHeight](/slides/php-java/datalabel/getactualheight/)() | float | Specifies actual height of the chart element. Call method IChart.ValidateChartLayout() before to get actual values. Read float. |
| [getActualLabelText](/slides/php-java/datalabel/getactuallabeltext/)() | String | Returns actual label text based on DataLabelFormat settings or TextFrameForOverriding.Text value. |
| [getActualWidth](/slides/php-java/datalabel/getactualwidth/)() | float | Specifies actual width of the chart element. Call method IChart.ValidateChartLayout() before to get actual values. Read float. |
| [getActualX](/slides/php-java/datalabel/getactualx/)() | float | Specifies actual x location (left) of the chart element relative to the left top corner of the chart. Call method IChart.ValidateChartLayout() before to get actual values. Read float. |
| [getActualY](/slides/php-java/datalabel/getactualy/)() | float | Specifies actual top of the chart element relative to the left top corner of the chart. Call method IChart.ValidateChartLayout() before to get actual values. Read float. |
| [getBottom](/slides/php-java/datalabel/getbottom/)() | float | Bottom. Read-only float. |
| [getChart](/slides/php-java/datalabel/getchart/)() | IChart | Returns the parent chart. Read-only IChart. |
| [getDataLabelFormat](/slides/php-java/datalabel/getdatalabelformat/)() | IDataLabelFormat | Returns data label format. Read-only IDataLabelFormat. |
| [getHeight](/slides/php-java/datalabel/getheight/)() | float | Returns or sets the height of a title as a fraction of the height of the chart. Read/write float. |
| [getPresentation](/slides/php-java/datalabel/getpresentation/)() | IPresentation | Returns the parent presentation of a FillFormat. Read-only IPresentation. |
| [getRight](/slides/php-java/datalabel/getright/)() | float | Right. Read-only float. |
| [getSlide](/slides/php-java/datalabel/getslide/)() | IBaseSlide | Returns the parent slide of a FillFormat. Read-only BaseSlide. |
| [getTextFormat](/slides/php-java/datalabel/gettextformat/)() | IChartTextFormat | Returns text format. Read-only IChartTextFormat. |
| [getTextFrameForOverriding](/slides/php-java/datalabel/gettextframeforoverriding/)() | ITextFrame | Can contain a rich formatted text. If this property is not null then this formatted text value overrides auto-generated text of data label. Auto-generated text of data label means text that is managed by ShowSeriesName, ShowValue, ... properties and is formatted with the TextFormatManager.TextFormat property. Read-only ITextFrame. |
| [getValueFromCell](/slides/php-java/datalabel/getvaluefromcell/)() | IChartDataCell | Gets or sets workbook data cell. Applied if IDataLabelFormat.ShowLabelValueFromCell property equals true. |
| [getWidth](/slides/php-java/datalabel/getwidth/)() | float | Returns or sets the width of a title as a fraction of the width of the chart. Read/write float. |
| [getX](/slides/php-java/datalabel/getx/)() | float | Returns or sets the x coordinate of a title as a fraction of the width of the chart. Read/write float. |
| [getY](/slides/php-java/datalabel/gety/)() | float | Returns or sets the y coordinate of a title as a fraction of the height of the chart. Read/write float. |
| [hide](/slides/php-java/datalabel/hide/)() | void | Make data label hidden by setting all Show*-flags (ShowValue, ...) to false state. IsVisible will be false after this. If data label is not visible (IsVisible is false) you can make data label visible with setting Show*-flags (ShowValue, ...) to true state. |
| [isVisible](/slides/php-java/datalabel/isvisible/)() | boolean | False means that data label is not visible (and so all Show*-flags (ShowValue, ...) are false). Read-only boolean. If data label is visible you can make it hidden with Hide() method. But if data label is not visible (IsVisible is false) you can make data label visible with setting Show*-flags (ShowValue, ...) to true state. |
| [setHeight](/slides/php-java/datalabel/setheight/)(float) | void | Returns or sets the height of a title as a fraction of the height of the chart. Read/write float. |
| [setValueFromCell](/slides/php-java/datalabel/setvaluefromcell/)(IChartDataCell) | void | Gets or sets workbook data cell. Applied if IDataLabelFormat.ShowLabelValueFromCell property equals true. |
| [setWidth](/slides/php-java/datalabel/setwidth/)(float) | void | Returns or sets the width of a title as a fraction of the width of the chart. Read/write float. |
| [setX](/slides/php-java/datalabel/setx/)(float) | void | Returns or sets the x coordinate of a title as a fraction of the width of the chart. Read/write float. |
| [setY](/slides/php-java/datalabel/sety/)(float) | void | Returns or sets the y coordinate of a title as a fraction of the height of the chart. Read/write float. |

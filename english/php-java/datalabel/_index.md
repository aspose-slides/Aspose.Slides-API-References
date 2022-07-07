---
title: DataLabel
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/datalabel/
---

## DataLabel class

 Represents a series labels.
 

## Constructors

| Name | Description |
| --- | --- |
| [DataLabel](datalabel)(ChartDataPoint) | Creates a new instance of DataLabel class. |

## Methods

| Name | Description |
| --- | --- |
| [addTextFrameForOverriding](addtextframeforoverriding)(String) | Initialize TextFrameForOverriding with the text in paramener "text". If TextFrameForOverriding is already initialized then simply changes its text. |
| [getActualHeight](getactualheight)() | Specifies actual height of the chart element. Call method IChart.ValidateChartLayout() before to get actual values. Read float. |
| [getActualLabelText](getactuallabeltext)() | Returns actual label text based on DataLabelFormat settings or TextFrameForOverriding.Text value. |
| [getActualWidth](getactualwidth)() | Specifies actual width of the chart element. Call method IChart.ValidateChartLayout() before to get actual values. Read float. |
| [getActualX](getactualx)() | Specifies actual x location (left) of the chart element relative to the left top corner of the chart. Call method IChart.ValidateChartLayout() before to get actual values. Read float. |
| [getActualY](getactualy)() | Specifies actual top of the chart element relative to the left top corner of the chart. Call method IChart.ValidateChartLayout() before to get actual values. Read float. |
| [getBottom](getbottom)() | Bottom. Read-only float. |
| [getChart](getchart)() | Returns the parent chart. Read-only IChart. |
| [getDataLabelFormat](getdatalabelformat)() | Returns data label format. Read-only IDataLabelFormat. |
| [getHeight](getheight)() | Returns or sets the height of a title as a fraction of the height of the chart. Read/write float. |
| [getPresentation](getpresentation)() | Returns the parent presentation of a FillFormat. Read-only IPresentation. |
| [getRight](getright)() | Right. Read-only float. |
| [getSlide](getslide)() | Returns the parent slide of a FillFormat. Read-only BaseSlide. |
| [getTextFormat](gettextformat)() | Returns text format. Read-only IChartTextFormat. |
| [getTextFrameForOverriding](gettextframeforoverriding)() | Can contain a rich formatted text. If this property is not null then this formatted text value overrides auto-generated text of data label. Auto-generated text of data label means text that is managed by ShowSeriesName, ShowValue, ... properties and is formatted with the TextFormatManager.TextFormat property. Read-only ITextFrame. |
| [getValueFromCell](getvaluefromcell)() | Gets or sets workbook data cell. Applied if IDataLabelFormat.ShowLabelValueFromCell property equals true. |
| [getWidth](getwidth)() | Returns or sets the width of a title as a fraction of the width of the chart. Read/write float. |
| [getX](getx)() | Returns or sets the x coordinate of a title as a fraction of the width of the chart. Read/write float. |
| [getY](gety)() | Returns or sets the y coordinate of a title as a fraction of the height of the chart. Read/write float. |
| [hide](hide)() | Make data label hidden by setting all Show*-flags (ShowValue, ...) to false state. IsVisible will be false after this. If data label is not visible (IsVisible is false) you can make data label visible with setting Show*-flags (ShowValue, ...) to true state. |
| [isVisible](isvisible)() | False means that data label is not visible (and so all Show*-flags (ShowValue, ...) are false). Read-only boolean. If data label is visible you can make it hidden with Hide() method. But if data label is not visible (IsVisible is false) you can make data label visible with setting Show*-flags (ShowValue, ...) to true state. |
| [setHeight](setheight)(float) | Returns or sets the height of a title as a fraction of the height of the chart. Read/write float. |
| [setValueFromCell](setvaluefromcell)([ChartDataCell](../chartdatacell)) | Gets or sets workbook data cell. Applied if IDataLabelFormat.ShowLabelValueFromCell property equals true. |
| [setWidth](setwidth)(float) | Returns or sets the width of a title as a fraction of the width of the chart. Read/write float. |
| [setX](setx)(float) | Returns or sets the x coordinate of a title as a fraction of the width of the chart. Read/write float. |
| [setY](sety)(float) | Returns or sets the y coordinate of a title as a fraction of the height of the chart. Read/write float. |

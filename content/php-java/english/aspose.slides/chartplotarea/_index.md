---
title: ChartPlotArea
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/chartplotarea/
---

## ChartPlotArea class

 Represents rectangle where chart should be plotted.
 

## Methods

| Name | Description |
| --- | --- |
| [getActualHeight](getactualheight)() | Specifies actual height of the chart element. Call method IChart.ValidateChartLayout() before to get actual values. Read float. |
| [getActualWidth](getactualwidth)() | Specifies actual width of the chart element. Call method IChart.ValidateChartLayout() before to get actual values. Read float. |
| [getActualX](getactualx)() | Specifies actual x location (left) of the chart element relative to the left top corner of the chart. Call method IChart.ValidateChartLayout() before to get actual values. Read float. |
| [getActualY](getactualy)() | Specifies actual top of the chart element relative to the left top corner of the chart. Call method IChart.ValidateChartLayout() before to get actual values. Read float. |
| [getBottom](getbottom)() | Bottom. Read-only float. |
| [getChart](getchart)() | Chart. Read-only IChart. |
| [getFormat](getformat)() | Returns the format of a plot area. Read-only IFormat. |
| [getHeight](getheight)() | Returns or sets the height of a plot area bounding box as a fraction of the height of the chart (from 0 to 1). Read/write float. |
| [getLayoutTargetType](getlayouttargettype)() | If layout of the plot area defined manually this property specifies whether to layout the plot area by its inside (not including axis and axis labels) or outside (including axis and axis labels). Read/write LayoutTargetType( #getLayoutTargetType/ #setLayoutTargetType(int)). Presentation presentation = new Presentation(); try { ISlide slide = presentation.getSlides().get_Item(0); IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 20, 100, 600, 400); chart.getPlotArea().setX(0.2f); chart.getPlotArea().setY(0.2f); chart.getPlotArea().setWidth(0.7f); chart.getPlotArea().setHeight(0.7f); chart.getPlotArea().setLayoutTargetType(LayoutTargetType.Inner); ... } finally { if (presentation != null) presentation.dispose(); } |
| [getPresentation](getpresentation)() | Returns the parent presentation of a FillFormat. Read-only IPresentation. |
| [getRight](getright)() | Right. Read-only float. |
| [getSlide](getslide)() | Returns the parent slide of a FillFormat. Read-only BaseSlide. |
| [getWidth](getwidth)() | Returns or sets the width of a plot area bounding box as a fraction of the width of the chart (from 0 to 1). Read/write float. |
| [getX](getx)() | Returns or sets the x coordinate of the upper left corner of plot area bounding box as a fraction of the width of the chart (from 0 to 1). Read/write float. |
| [getY](gety)() | Returns or sets the y coordinate of the upper left corner of plot area bounding box as a fraction of the height of the chart (from 0 to 1). Read/write float. |
| [isLocationAutocalculated](islocationautocalculated)() | Defines how location should be calculated: true – calculated automatically; defined by the X, Y, Width, Height properties. Read-only boolean. |
| [setHeight](setheight)(float) | Returns or sets the height of a plot area bounding box as a fraction of the height of the chart (from 0 to 1). Read/write float. |
| [setLayoutTargetType](setlayouttargettype)(int) | If layout of the plot area defined manually this property specifies whether to layout the plot area by its inside (not including axis and axis labels) or outside (including axis and axis labels). Read/write LayoutTargetType( #getLayoutTargetType/ #setLayoutTargetType(int)). Presentation presentation = new Presentation(); try { ISlide slide = presentation.getSlides().get_Item(0); IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 20, 100, 600, 400); chart.getPlotArea().setX(0.2f); chart.getPlotArea().setY(0.2f); chart.getPlotArea().setWidth(0.7f); chart.getPlotArea().setHeight(0.7f); chart.getPlotArea().setLayoutTargetType(LayoutTargetType.Inner); ... } finally { if (presentation != null) presentation.dispose(); } |
| [setWidth](setwidth)(float) | Returns or sets the width of a plot area bounding box as a fraction of the width of the chart (from 0 to 1). Read/write float. |
| [setX](setx)(float) | Returns or sets the x coordinate of the upper left corner of plot area bounding box as a fraction of the width of the chart (from 0 to 1). Read/write float. |
| [setY](sety)(float) | Returns or sets the y coordinate of the upper left corner of plot area bounding box as a fraction of the height of the chart (from 0 to 1). Read/write float. |

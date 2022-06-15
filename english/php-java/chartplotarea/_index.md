---
title: ChartPlotArea
type: docs
weight: 0
url: /php-java/chartplotarea/
---

# ChartPlotArea class

 Represents rectangle where chart should be plotted.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [getActualHeight](/slides/php-java/chartplotarea/getactualheight/)() | float | Specifies actual height of the chart element. Call method IChart.ValidateChartLayout() before to get actual values. Read float. |
| [getActualWidth](/slides/php-java/chartplotarea/getactualwidth/)() | float | Specifies actual width of the chart element. Call method IChart.ValidateChartLayout() before to get actual values. Read float. |
| [getActualX](/slides/php-java/chartplotarea/getactualx/)() | float | Specifies actual x location (left) of the chart element relative to the left top corner of the chart. Call method IChart.ValidateChartLayout() before to get actual values. Read float. |
| [getActualY](/slides/php-java/chartplotarea/getactualy/)() | float | Specifies actual top of the chart element relative to the left top corner of the chart. Call method IChart.ValidateChartLayout() before to get actual values. Read float. |
| [getBottom](/slides/php-java/chartplotarea/getbottom/)() | float | Bottom. Read-only float. |
| [getChart](/slides/php-java/chartplotarea/getchart/)() | IChart | Chart. Read-only IChart. |
| [getFormat](/slides/php-java/chartplotarea/getformat/)() | IFormat | Returns the format of a plot area. Read-only IFormat. |
| [getHeight](/slides/php-java/chartplotarea/getheight/)() | float | Returns or sets the height of a plot area bounding box as a fraction of the height of the chart (from 0 to 1). Read/write float. |
| [getLayoutTargetType](/slides/php-java/chartplotarea/getlayouttargettype/)() | int | If layout of the plot area defined manually this property specifies whether to layout the plot area by its inside (not including axis and axis labels) or outside (including axis and axis labels). Read/write LayoutTargetType( #getLayoutTargetType/ #setLayoutTargetType(int)). Presentation presentation = new Presentation(); try { ISlide slide = presentation.getSlides().get_Item(0); IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 20, 100, 600, 400); chart.getPlotArea().setX(0.2f); chart.getPlotArea().setY(0.2f); chart.getPlotArea().setWidth(0.7f); chart.getPlotArea().setHeight(0.7f); chart.getPlotArea().setLayoutTargetType(LayoutTargetType.Inner); ... } finally { if (presentation != null) presentation.dispose(); } |
| [getPresentation](/slides/php-java/chartplotarea/getpresentation/)() | IPresentation | Returns the parent presentation of a FillFormat. Read-only IPresentation. |
| [getRight](/slides/php-java/chartplotarea/getright/)() | float | Right. Read-only float. |
| [getSlide](/slides/php-java/chartplotarea/getslide/)() | IBaseSlide | Returns the parent slide of a FillFormat. Read-only BaseSlide. |
| [getWidth](/slides/php-java/chartplotarea/getwidth/)() | float | Returns or sets the width of a plot area bounding box as a fraction of the width of the chart (from 0 to 1). Read/write float. |
| [getX](/slides/php-java/chartplotarea/getx/)() | float | Returns or sets the x coordinate of the upper left corner of plot area bounding box as a fraction of the width of the chart (from 0 to 1). Read/write float. |
| [getY](/slides/php-java/chartplotarea/gety/)() | float | Returns or sets the y coordinate of the upper left corner of plot area bounding box as a fraction of the height of the chart (from 0 to 1). Read/write float. |
| [isLocationAutocalculated](/slides/php-java/chartplotarea/islocationautocalculated/)() | boolean | Defines how location should be calculated: true – calculated automatically; defined by the X, Y, Width, Height properties. Read-only boolean. |
| [setHeight](/slides/php-java/chartplotarea/setheight/)(float) | void | Returns or sets the height of a plot area bounding box as a fraction of the height of the chart (from 0 to 1). Read/write float. |
| [setLayoutTargetType](/slides/php-java/chartplotarea/setlayouttargettype/)(int) | void | If layout of the plot area defined manually this property specifies whether to layout the plot area by its inside (not including axis and axis labels) or outside (including axis and axis labels). Read/write LayoutTargetType( #getLayoutTargetType/ #setLayoutTargetType(int)). Presentation presentation = new Presentation(); try { ISlide slide = presentation.getSlides().get_Item(0); IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 20, 100, 600, 400); chart.getPlotArea().setX(0.2f); chart.getPlotArea().setY(0.2f); chart.getPlotArea().setWidth(0.7f); chart.getPlotArea().setHeight(0.7f); chart.getPlotArea().setLayoutTargetType(LayoutTargetType.Inner); ... } finally { if (presentation != null) presentation.dispose(); } |
| [setWidth](/slides/php-java/chartplotarea/setwidth/)(float) | void | Returns or sets the width of a plot area bounding box as a fraction of the width of the chart (from 0 to 1). Read/write float. |
| [setX](/slides/php-java/chartplotarea/setx/)(float) | void | Returns or sets the x coordinate of the upper left corner of plot area bounding box as a fraction of the width of the chart (from 0 to 1). Read/write float. |
| [setY](/slides/php-java/chartplotarea/sety/)(float) | void | Returns or sets the y coordinate of the upper left corner of plot area bounding box as a fraction of the height of the chart (from 0 to 1). Read/write float. |

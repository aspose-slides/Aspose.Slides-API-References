---
title: Chart
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/aspose.slides/chart/
---

## Chart class

 Represents an graphic chart on a slide.
 

## Methods

| Name | Description |
| --- | --- |
| [createThemeEffective](createthemeeffective)() | Returns an effective theme for this chart. |
| [getAxes](getaxes)() | Provide access to chart axes. Read-only IAxesManager. |
| [getBackWall](getbackwall)() | Returns an object which allows to change format of the back wall of a 3D chart. Read-only IChartWall. |
| [getChart](getchart)() |  |
| [getChartData](getchartdata)() | Returns information about the linked or embedded data associated with a chart. Read-only IChartData. |
| [getChartDataTable](getchartdatatable)() | Returns a data table of a chart. Read-only IDataTable. |
| [getChartTitle](getcharttitle)() | Returns or sets a chart title. Read-only IChartTitle. |
| [getDisplayBlanksAs](getdisplayblanksas)() | Returns or sets the way to plot blank cells on a chart. Read/write DisplayBlanksAsType. |
| [getFloor](getfloor)() | Returns an object which allows to change format of the floor of a 3D chart. Read-only IChartWall. |
| [getLegend](getlegend)() | Returns or sets a legend for a chart. Read-only ILegend. |
| [getPlotArea](getplotarea)() | Represents the plot area of a chart. Read-only IChartPlotArea. |
| [getPlotVisibleCellsOnly](getplotvisiblecellsonly)() | Determines whether the only visible cells are plotted. False to plot both visible and hidden cells. Read/write boolean. |
| [getRotation3D](getrotation3d)() | Returns a 3D rotation of a chart. Read-only IRotation3D. |
| [getShowDataLabelsOverMaximum](getshowdatalabelsovermaximum)() | Specifies data labels over the maximum of the chart shall be shown. Read/write boolean. |
| [getSideWall](getsidewall)() | Returns an object which allows to change format of the side wall of a 3D chart. Read-only IChartWall. |
| [getStyle](getstyle)() | Returns or sets the chart style. Read/write StyleType. |
| [getTextFormat](gettextformat)() | Returns chart text format. The property is not applicable for the following types: ChartType#Treemap, ChartType#Sunburst, ChartType#Waterfall, ChartType#Histogram, ChartType#Funnel, ChartType#BoxAndWhisker. Read-only IChartTextFormat. |
| [getThemeManager](getthememanager)() | Returns theme manager. Read-only IOverrideThemeManager. |
| [getType](gettype)() | Returns or sets the chart type. Read/write ChartType. |
| [getUserShapes](getusershapes)() | Specify the shapes drawn on top of the chart. Read-only IGroupShape. |
| [hasDataTable](hasdatatable)() | Determines whether a chart has a data table. Read/write boolean. |
| [hasLegend](haslegend)() | Determines whether a chart has a legend. Read/write boolean. |
| [hasRoundedCorners](hasroundedcorners)() | Specifies the chart area shall have rounded corners. Read/write boolean. |
| [hasTitle](hastitle)() | Determines whether a chart has a visible title. Read/write boolean. |
| [setDataTable](setdatatable)(boolean) | Determines whether a chart has a data table. Read/write boolean. |
| [setDisplayBlanksAs](setdisplayblanksas)(int) | Returns or sets the way to plot blank cells on a chart. Read/write DisplayBlanksAsType. |
| [setLegend](setlegend)(boolean) | Determines whether a chart has a legend. Read/write boolean. |
| [setPlotVisibleCellsOnly](setplotvisiblecellsonly)(boolean) | Determines whether the only visible cells are plotted. False to plot both visible and hidden cells. Read/write boolean. |
| [setRoundedCorners](setroundedcorners)(boolean) | Specifies the chart area shall have rounded corners. Read/write boolean. |
| [setShowDataLabelsOverMaximum](setshowdatalabelsovermaximum)(boolean) | Specifies data labels over the maximum of the chart shall be shown. Read/write boolean. |
| [setStyle](setstyle)(int) | Returns or sets the chart style. Read/write StyleType. |
| [setTitle](settitle)(boolean) | Determines whether a chart has a visible title. Read/write boolean. |
| [setType](settype)(int) | Returns or sets the chart type. Read/write ChartType. |
| [validateChartLayout](validatechartlayout)() | Calculates actual values of chart elements. The actual values include position of elements that implement IActualLayout interface (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) and actual axes values (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |

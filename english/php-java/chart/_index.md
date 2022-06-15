---
title: Chart
type: docs
weight: 0
url: /php-java/chart/
---

# Chart class

 Represents an graphic chart on a slide.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [createThemeEffective](/slides/php-java/chart/createthemeeffective/)() | IThemeEffectiveData | Returns an effective theme for this chart. |
| [getAxes](/slides/php-java/chart/getaxes/)() | IAxesManager | Provide access to chart axes. Read-only IAxesManager. |
| [getBackWall](/slides/php-java/chart/getbackwall/)() | IChartWall | Returns an object which allows to change format of the back wall of a 3D chart. Read-only IChartWall. |
| [getChart](/slides/php-java/chart/getchart/)() | IChart |  |
| [getChartData](/slides/php-java/chart/getchartdata/)() | IChartData | Returns information about the linked or embedded data associated with a chart. Read-only IChartData. |
| [getChartDataTable](/slides/php-java/chart/getchartdatatable/)() | IDataTable | Returns a data table of a chart. Read-only IDataTable. |
| [getChartTitle](/slides/php-java/chart/getcharttitle/)() | IChartTitle | Returns or sets a chart title. Read-only IChartTitle. |
| [getDisplayBlanksAs](/slides/php-java/chart/getdisplayblanksas/)() | int | Returns or sets the way to plot blank cells on a chart. Read/write DisplayBlanksAsType. |
| [getFloor](/slides/php-java/chart/getfloor/)() | IChartWall | Returns an object which allows to change format of the floor of a 3D chart. Read-only IChartWall. |
| [getLegend](/slides/php-java/chart/getlegend/)() | ILegend | Returns or sets a legend for a chart. Read-only ILegend. |
| [getPlotArea](/slides/php-java/chart/getplotarea/)() | IChartPlotArea | Represents the plot area of a chart. Read-only IChartPlotArea. |
| [getPlotVisibleCellsOnly](/slides/php-java/chart/getplotvisiblecellsonly/)() | boolean | Determines whether the only visible cells are plotted. False to plot both visible and hidden cells. Read/write boolean. |
| [getRotation3D](/slides/php-java/chart/getrotation3d/)() | IRotation3D | Returns a 3D rotation of a chart. Read-only IRotation3D. |
| [getShowDataLabelsOverMaximum](/slides/php-java/chart/getshowdatalabelsovermaximum/)() | boolean | Specifies data labels over the maximum of the chart shall be shown. Read/write boolean. |
| [getSideWall](/slides/php-java/chart/getsidewall/)() | IChartWall | Returns an object which allows to change format of the side wall of a 3D chart. Read-only IChartWall. |
| [getStyle](/slides/php-java/chart/getstyle/)() | int | Returns or sets the chart style. Read/write StyleType. |
| [getTextFormat](/slides/php-java/chart/gettextformat/)() | IChartTextFormat | Returns chart text format. The property is not applicable for the following types: ChartType#Treemap, ChartType#Sunburst, ChartType#Waterfall, ChartType#Histogram, ChartType#Funnel, ChartType#BoxAndWhisker. Read-only IChartTextFormat. |
| [getThemeManager](/slides/php-java/chart/getthememanager/)() | IOverrideThemeManager | Returns theme manager. Read-only IOverrideThemeManager. |
| [getType](/slides/php-java/chart/gettype/)() | int | Returns or sets the chart type. Read/write ChartType. |
| [getUserShapes](/slides/php-java/chart/getusershapes/)() | IGroupShape | Specify the shapes drawn on top of the chart. Read-only IGroupShape. |
| [hasDataTable](/slides/php-java/chart/hasdatatable/)() | boolean | Determines whether a chart has a data table. Read/write boolean. |
| [hasLegend](/slides/php-java/chart/haslegend/)() | boolean | Determines whether a chart has a legend. Read/write boolean. |
| [hasRoundedCorners](/slides/php-java/chart/hasroundedcorners/)() | boolean | Specifies the chart area shall have rounded corners. Read/write boolean. |
| [hasTitle](/slides/php-java/chart/hastitle/)() | boolean | Determines whether a chart has a visible title. Read/write boolean. |
| [setDataTable](/slides/php-java/chart/setdatatable/)(boolean) | void | Determines whether a chart has a data table. Read/write boolean. |
| [setDisplayBlanksAs](/slides/php-java/chart/setdisplayblanksas/)(int) | void | Returns or sets the way to plot blank cells on a chart. Read/write DisplayBlanksAsType. |
| [setLegend](/slides/php-java/chart/setlegend/)(boolean) | void | Determines whether a chart has a legend. Read/write boolean. |
| [setPlotVisibleCellsOnly](/slides/php-java/chart/setplotvisiblecellsonly/)(boolean) | void | Determines whether the only visible cells are plotted. False to plot both visible and hidden cells. Read/write boolean. |
| [setRoundedCorners](/slides/php-java/chart/setroundedcorners/)(boolean) | void | Specifies the chart area shall have rounded corners. Read/write boolean. |
| [setShowDataLabelsOverMaximum](/slides/php-java/chart/setshowdatalabelsovermaximum/)(boolean) | void | Specifies data labels over the maximum of the chart shall be shown. Read/write boolean. |
| [setStyle](/slides/php-java/chart/setstyle/)(int) | void | Returns or sets the chart style. Read/write StyleType. |
| [setTitle](/slides/php-java/chart/settitle/)(boolean) | void | Determines whether a chart has a visible title. Read/write boolean. |
| [setType](/slides/php-java/chart/settype/)(int) | void | Returns or sets the chart type. Read/write ChartType. |
| [validateChartLayout](/slides/php-java/chart/validatechartlayout/)() | void | Calculates actual values of chart elements. The actual values include position of elements that implement IActualLayout interface (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) and actual axes values (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |

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
| [createThemeEffective](/php-java/chart/createthemeeffective/)() | IThemeEffectiveData | Returns an effective theme for this chart. |
| [getAxes](/php-java/chart/getaxes/)() | IAxesManager | Provide access to chart axes. Read-only IAxesManager. |
| [getBackWall](/php-java/chart/getbackwall/)() | IChartWall | Returns an object which allows to change format of the back wall of a 3D chart. Read-only IChartWall. |
| [getChart](/php-java/chart/getchart/)() | IChart |  |
| [getChartData](/php-java/chart/getchartdata/)() | IChartData | Returns information about the linked or embedded data associated with a chart. Read-only IChartData. |
| [getChartDataTable](/php-java/chart/getchartdatatable/)() | IDataTable | Returns a data table of a chart. Read-only IDataTable. |
| [getChartTitle](/php-java/chart/getcharttitle/)() | IChartTitle | Returns or sets a chart title. Read-only IChartTitle. |
| [getDisplayBlanksAs](/php-java/chart/getdisplayblanksas/)() | int | Returns or sets the way to plot blank cells on a chart. Read/write DisplayBlanksAsType. |
| [getFloor](/php-java/chart/getfloor/)() | IChartWall | Returns an object which allows to change format of the floor of a 3D chart. Read-only IChartWall. |
| [getLegend](/php-java/chart/getlegend/)() | ILegend | Returns or sets a legend for a chart. Read-only ILegend. |
| [getPlotArea](/php-java/chart/getplotarea/)() | IChartPlotArea | Represents the plot area of a chart. Read-only IChartPlotArea. |
| [getPlotVisibleCellsOnly](/php-java/chart/getplotvisiblecellsonly/)() | boolean | Determines whether the only visible cells are plotted. False to plot both visible and hidden cells. Read/write boolean. |
| [getRotation3D](/php-java/chart/getrotation3d/)() | IRotation3D | Returns a 3D rotation of a chart. Read-only IRotation3D. |
| [getShowDataLabelsOverMaximum](/php-java/chart/getshowdatalabelsovermaximum/)() | boolean | Specifies data labels over the maximum of the chart shall be shown. Read/write boolean. |
| [getSideWall](/php-java/chart/getsidewall/)() | IChartWall | Returns an object which allows to change format of the side wall of a 3D chart. Read-only IChartWall. |
| [getStyle](/php-java/chart/getstyle/)() | int | Returns or sets the chart style. Read/write StyleType. |
| [getTextFormat](/php-java/chart/gettextformat/)() | IChartTextFormat | Returns chart text format. The property is not applicable for the following types: ChartType#Treemap, ChartType#Sunburst, ChartType#Waterfall, ChartType#Histogram, ChartType#Funnel, ChartType#BoxAndWhisker. Read-only IChartTextFormat. |
| [getThemeManager](/php-java/chart/getthememanager/)() | IOverrideThemeManager | Returns theme manager. Read-only IOverrideThemeManager. |
| [getType](/php-java/chart/gettype/)() | int | Returns or sets the chart type. Read/write ChartType. |
| [getUserShapes](/php-java/chart/getusershapes/)() | IGroupShape | Specify the shapes drawn on top of the chart. Read-only IGroupShape. |
| [hasDataTable](/php-java/chart/hasdatatable/)() | boolean | Determines whether a chart has a data table. Read/write boolean. |
| [hasLegend](/php-java/chart/haslegend/)() | boolean | Determines whether a chart has a legend. Read/write boolean. |
| [hasRoundedCorners](/php-java/chart/hasroundedcorners/)() | boolean | Specifies the chart area shall have rounded corners. Read/write boolean. |
| [hasTitle](/php-java/chart/hastitle/)() | boolean | Determines whether a chart has a visible title. Read/write boolean. |
| [setDataTable](/php-java/chart/setdatatable/)(boolean) | void | Determines whether a chart has a data table. Read/write boolean. |
| [setDisplayBlanksAs](/php-java/chart/setdisplayblanksas/)(int) | void | Returns or sets the way to plot blank cells on a chart. Read/write DisplayBlanksAsType. |
| [setLegend](/php-java/chart/setlegend/)(boolean) | void | Determines whether a chart has a legend. Read/write boolean. |
| [setPlotVisibleCellsOnly](/php-java/chart/setplotvisiblecellsonly/)(boolean) | void | Determines whether the only visible cells are plotted. False to plot both visible and hidden cells. Read/write boolean. |
| [setRoundedCorners](/php-java/chart/setroundedcorners/)(boolean) | void | Specifies the chart area shall have rounded corners. Read/write boolean. |
| [setShowDataLabelsOverMaximum](/php-java/chart/setshowdatalabelsovermaximum/)(boolean) | void | Specifies data labels over the maximum of the chart shall be shown. Read/write boolean. |
| [setStyle](/php-java/chart/setstyle/)(int) | void | Returns or sets the chart style. Read/write StyleType. |
| [setTitle](/php-java/chart/settitle/)(boolean) | void | Determines whether a chart has a visible title. Read/write boolean. |
| [setType](/php-java/chart/settype/)(int) | void | Returns or sets the chart type. Read/write ChartType. |
| [validateChartLayout](/php-java/chart/validatechartlayout/)() | void | Calculates actual values of chart elements. The actual values include position of elements that implement IActualLayout interface (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) and actual axes values (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |

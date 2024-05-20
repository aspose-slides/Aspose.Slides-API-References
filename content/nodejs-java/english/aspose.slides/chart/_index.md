---
title: Chart
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/chart/
---

## Chart class

 Represents an graphic chart on a slide.
 
### createThemeEffective {#createThemeEffective}

| Name | Description |
| --- | --- |
| createThemeEffective () | Returns an effective theme for this chart. |

 **Returns:**
ThemeEffectiveData


---


### getAxes {#getAxes}

| Name | Description |
| --- | --- |
| getAxes () | Provide access to chart axes. Read-only IAxesManager. |

 **Returns:**
[AxesManager](../axesmanager)


---


### getBackWall {#getBackWall}

| Name | Description |
| --- | --- |
| getBackWall () | Returns an object which allows to change format of the back wall of a 3D chart. Read-only IChartWall. |

 **Returns:**
[ChartWall](../chartwall)


---


### getChart {#getChart}

| Name | Description |
| --- | --- |
| getChart () |  |

 **Returns:**
[Chart](../chart)


---


### getChartData {#getChartData}

| Name | Description |
| --- | --- |
| getChartData () | Returns information about the linked or embedded data associated with a chart. Read-only IChartData. |

 **Returns:**
[ChartData](../chartdata)


---


### getChartDataTable {#getChartDataTable}

| Name | Description |
| --- | --- |
| getChartDataTable () | Returns a data table of a chart. Read-only IDataTable. |

 **Returns:**
[DataTable](../datatable)


---


### getChartTitle {#getChartTitle}

| Name | Description |
| --- | --- |
| getChartTitle () | Returns or sets a chart title. Read-only IChartTitle. |

 **Returns:**
[ChartTitle](../charttitle)


---


### getDisplayBlanksAs {#getDisplayBlanksAs}

| Name | Description |
| --- | --- |
| getDisplayBlanksAs () | Returns or sets the way to plot blank cells on a chart. Read/write DisplayBlanksAsType. |

 **Returns:**
int


---


### getFloor {#getFloor}

| Name | Description |
| --- | --- |
| getFloor () | Returns an object which allows to change format of the floor of a 3D chart. Read-only IChartWall. |

 **Returns:**
[ChartWall](../chartwall)


---


### getLegend {#getLegend}

| Name | Description |
| --- | --- |
| getLegend () | Returns or sets a legend for a chart. Read-only ILegend. |

 **Returns:**
[Legend](../legend)


---


### getPlotArea {#getPlotArea}

| Name | Description |
| --- | --- |
| getPlotArea () | Represents the plot area of a chart. Read-only IChartPlotArea. |

 **Returns:**
[ChartPlotArea](../chartplotarea)


---


### getPlotVisibleCellsOnly {#getPlotVisibleCellsOnly}

| Name | Description |
| --- | --- |
| getPlotVisibleCellsOnly () | Determines whether the only visible cells are plotted. False to plot both visible and hidden cells. Read/write boolean. |

 **Returns:**
boolean


---


### getRotation3D {#getRotation3D}

| Name | Description |
| --- | --- |
| getRotation3D () | Returns a 3D rotation of a chart. Read-only IRotation3D. |

 **Returns:**
[Rotation3D](../rotation3d)


---


### getShowDataLabelsOverMaximum {#getShowDataLabelsOverMaximum}

| Name | Description |
| --- | --- |
| getShowDataLabelsOverMaximum () | Specifies data labels over the maximum of the chart shall be shown. Read/write boolean. |

 **Returns:**
boolean


---


### getSideWall {#getSideWall}

| Name | Description |
| --- | --- |
| getSideWall () | Returns an object which allows to change format of the side wall of a 3D chart. Read-only IChartWall. |

 **Returns:**
[ChartWall](../chartwall)


---


### getStyle {#getStyle}

| Name | Description |
| --- | --- |
| getStyle () | Returns or sets the chart style. Read/write StyleType. |

 **Returns:**
int


---


### getTextFormat {#getTextFormat}

| Name | Description |
| --- | --- |
| getTextFormat () | Returns chart text format. The property is not applicable for the following types: ChartType#Treemap, ChartType#Sunburst, ChartType#Waterfall, ChartType#Histogram, ChartType#Funnel, ChartType#BoxAndWhisker. Read-only IChartTextFormat. |

 **Returns:**
[ChartTextFormat](../charttextformat)


---


### getThemeManager {#getThemeManager}

| Name | Description |
| --- | --- |
| getThemeManager () | Returns theme manager. Read-only IOverrideThemeManager. |

 **Returns:**
[BaseOverrideThemeManager](../baseoverridethememanager), [NotesSlideThemeManager](../notesslidethememanager), [ChartThemeManager](../chartthememanager), [SlideThemeManager](../slidethememanager), [LayoutSlideThemeManager](../layoutslidethememanager)


---


### getType {#getType}

| Name | Description |
| --- | --- |
| getType () | Returns or sets the chart type. Read/write ChartType. |

 **Returns:**
int


---


### getUserShapes {#getUserShapes}

| Name | Description |
| --- | --- |
| getUserShapes () | Specify the shapes drawn on top of the chart. Read-only IGroupShape. |

 **Returns:**
[GroupShape](../groupshape)


---


### hasDataTable {#hasDataTable}

| Name | Description |
| --- | --- |
| hasDataTable () | Determines whether a chart has a data table. Read/write boolean. |

 **Returns:**
boolean


---


### hasLegend {#hasLegend}

| Name | Description |
| --- | --- |
| hasLegend () | Determines whether a chart has a legend. Read/write boolean. |

 **Returns:**
boolean


---


### hasRoundedCorners {#hasRoundedCorners}

| Name | Description |
| --- | --- |
| hasRoundedCorners () | Specifies the chart area shall have rounded corners. Read/write boolean. |

 **Returns:**
boolean


---


### hasTitle {#hasTitle}

| Name | Description |
| --- | --- |
| hasTitle () | Determines whether a chart has a visible title. Read/write boolean. |

 **Returns:**
boolean


---


### setDataTable {#setDataTable}

| Name | Description |
| --- | --- |
| setDataTable (boolean) | Determines whether a chart has a data table. Read/write boolean. |


---


### setDisplayBlanksAs {#setDisplayBlanksAs}

| Name | Description |
| --- | --- |
| setDisplayBlanksAs (int) | Returns or sets the way to plot blank cells on a chart. Read/write DisplayBlanksAsType. |


---


### setLegend {#setLegend}

| Name | Description |
| --- | --- |
| setLegend (boolean) | Determines whether a chart has a legend. Read/write boolean. |


---


### setPlotVisibleCellsOnly {#setPlotVisibleCellsOnly}

| Name | Description |
| --- | --- |
| setPlotVisibleCellsOnly (boolean) | Determines whether the only visible cells are plotted. False to plot both visible and hidden cells. Read/write boolean. |


---


### setRoundedCorners {#setRoundedCorners}

| Name | Description |
| --- | --- |
| setRoundedCorners (boolean) | Specifies the chart area shall have rounded corners. Read/write boolean. |


---


### setShowDataLabelsOverMaximum {#setShowDataLabelsOverMaximum}

| Name | Description |
| --- | --- |
| setShowDataLabelsOverMaximum (boolean) | Specifies data labels over the maximum of the chart shall be shown. Read/write boolean. |


---


### setStyle {#setStyle}

| Name | Description |
| --- | --- |
| setStyle (int) | Returns or sets the chart style. Read/write StyleType. |


---


### setTitle {#setTitle}

| Name | Description |
| --- | --- |
| setTitle (boolean) | Determines whether a chart has a visible title. Read/write boolean. |


---


### setType {#setType}

| Name | Description |
| --- | --- |
| setType (int) | Returns or sets the chart type. Read/write ChartType. |


---


### validateChartLayout {#validateChartLayout}

| Name | Description |
| --- | --- |
| validateChartLayout () | Calculates actual values of chart elements. The actual values include position of elements that implement IActualLayout interface (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) and actual axes values (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |


---



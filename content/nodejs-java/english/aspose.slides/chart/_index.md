---
title: Chart
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/chart/
---

## Chart class

 Represents an graphic chart on a slide.
 
| Name | Description |
| --- | --- |
| createThemeEffective () | Returns an effective theme for this chart. |

### Result
ThemeEffectiveData


---


| Name | Description |
| --- | --- |
| getAxes () | Provide access to chart axes. Read-only IAxesManager. |

### Result
AxesManager(../../axesmanager)


---


| Name | Description |
| --- | --- |
| getBackWall () | Returns an object which allows to change format of the back wall of a 3D chart. Read-only IChartWall. |

### Result
ChartWall(../../chartwall)


---


| Name | Description |
| --- | --- |
| getChart () |  |

### Result
Chart(../../chart)


---


| Name | Description |
| --- | --- |
| getChartData () | Returns information about the linked or embedded data associated with a chart. Read-only IChartData. |

### Result
ChartData(../../chartdata)


---


| Name | Description |
| --- | --- |
| getChartDataTable () | Returns a data table of a chart. Read-only IDataTable. |

### Result
DataTable(../../datatable)


---


| Name | Description |
| --- | --- |
| getChartTitle () | Returns or sets a chart title. Read-only IChartTitle. |

### Result
ChartTitle(../../charttitle)


---


| Name | Description |
| --- | --- |
| getDisplayBlanksAs () | Returns or sets the way to plot blank cells on a chart. Read/write DisplayBlanksAsType. |

### Result
int


---


| Name | Description |
| --- | --- |
| getFloor () | Returns an object which allows to change format of the floor of a 3D chart. Read-only IChartWall. |

### Result
ChartWall(../../chartwall)


---


| Name | Description |
| --- | --- |
| getLegend () | Returns or sets a legend for a chart. Read-only ILegend. |

### Result
Legend(../../legend)


---


| Name | Description |
| --- | --- |
| getPlotArea () | Represents the plot area of a chart. Read-only IChartPlotArea. |

### Result
ChartPlotArea(../../chartplotarea)


---


| Name | Description |
| --- | --- |
| getPlotVisibleCellsOnly () | Determines whether the only visible cells are plotted. False to plot both visible and hidden cells. Read/write boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| getRotation3D () | Returns a 3D rotation of a chart. Read-only IRotation3D. |

### Result
Rotation3D(../../rotation3d)


---


| Name | Description |
| --- | --- |
| getShowDataLabelsOverMaximum () | Specifies data labels over the maximum of the chart shall be shown. Read/write boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| getSideWall () | Returns an object which allows to change format of the side wall of a 3D chart. Read-only IChartWall. |

### Result
ChartWall(../../chartwall)


---


| Name | Description |
| --- | --- |
| getStyle () | Returns or sets the chart style. Read/write StyleType. |

### Result
int


---


| Name | Description |
| --- | --- |
| getTextFormat () | Returns chart text format. The property is not applicable for the following types: ChartType#Treemap, ChartType#Sunburst, ChartType#Waterfall, ChartType#Histogram, ChartType#Funnel, ChartType#BoxAndWhisker. Read-only IChartTextFormat. |

### Result
ChartTextFormat(../../charttextformat)


---


| Name | Description |
| --- | --- |
| getThemeManager () | Returns theme manager. Read-only IOverrideThemeManager. |

### Result
NotesSlideThemeManager(../../notesslidethememanager), ChartThemeManager(../../chartthememanager), BaseOverrideThemeManager(../../baseoverridethememanager), LayoutSlideThemeManager(../../layoutslidethememanager), SlideThemeManager(../../slidethememanager)


---


| Name | Description |
| --- | --- |
| getType () | Returns or sets the chart type. Read/write ChartType. |

### Result
int


---


| Name | Description |
| --- | --- |
| getUserShapes () | Specify the shapes drawn on top of the chart. Read-only IGroupShape. |

### Result
GroupShape(../../groupshape)


---


| Name | Description |
| --- | --- |
| hasDataTable () | Determines whether a chart has a data table. Read/write boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| hasLegend () | Determines whether a chart has a legend. Read/write boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| hasRoundedCorners () | Specifies the chart area shall have rounded corners. Read/write boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| hasTitle () | Determines whether a chart has a visible title. Read/write boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| setDataTable (boolean) | Determines whether a chart has a data table. Read/write boolean. |


---


| Name | Description |
| --- | --- |
| setDisplayBlanksAs (int) | Returns or sets the way to plot blank cells on a chart. Read/write DisplayBlanksAsType. |


---


| Name | Description |
| --- | --- |
| setLegend (boolean) | Determines whether a chart has a legend. Read/write boolean. |


---


| Name | Description |
| --- | --- |
| setPlotVisibleCellsOnly (boolean) | Determines whether the only visible cells are plotted. False to plot both visible and hidden cells. Read/write boolean. |


---


| Name | Description |
| --- | --- |
| setRoundedCorners (boolean) | Specifies the chart area shall have rounded corners. Read/write boolean. |


---


| Name | Description |
| --- | --- |
| setShowDataLabelsOverMaximum (boolean) | Specifies data labels over the maximum of the chart shall be shown. Read/write boolean. |


---


| Name | Description |
| --- | --- |
| setStyle (int) | Returns or sets the chart style. Read/write StyleType. |


---


| Name | Description |
| --- | --- |
| setTitle (boolean) | Determines whether a chart has a visible title. Read/write boolean. |


---


| Name | Description |
| --- | --- |
| setType (int) | Returns or sets the chart type. Read/write ChartType. |


---


| Name | Description |
| --- | --- |
| validateChartLayout () | Calculates actual values of chart elements. The actual values include position of elements that implement IActualLayout interface (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) and actual axes values (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |


---



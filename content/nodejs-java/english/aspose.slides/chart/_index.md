---
title: Chart
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/chart/
---

## Chart class

 Represents an graphic chart on a slide.
 

## Functions

| Name | Description |
| --- | --- |
| [createThemeEffective]() | Returns an effective theme for this chart. |

### Result
ThemeEffectiveData


---


| [getAxes]() | Provide access to chart axes. Read-only IAxesManager. |

### Result
[AxesManager](../../axesmanager)


---


| [getBackWall]() | Returns an object which allows to change format of the back wall of a 3D chart. Read-only IChartWall. |

### Result
[ChartWall](../../chartwall)


---


| [getChart]() |  |

### Result
[Chart](../../chart)


---


| [getChartData]() | Returns information about the linked or embedded data associated with a chart. Read-only IChartData. |

### Result
[ChartData](../../chartdata)


---


| [getChartDataTable]() | Returns a data table of a chart. Read-only IDataTable. |

### Result
[DataTable](../../datatable)


---


| [getChartTitle]() | Returns or sets a chart title. Read-only IChartTitle. |

### Result
[ChartTitle](../../charttitle)


---


| [getDisplayBlanksAs]() | Returns or sets the way to plot blank cells on a chart. Read/write DisplayBlanksAsType. |

### Result
int


---


| [getFloor]() | Returns an object which allows to change format of the floor of a 3D chart. Read-only IChartWall. |

### Result
[ChartWall](../../chartwall)


---


| [getLegend]() | Returns or sets a legend for a chart. Read-only ILegend. |

### Result
[Legend](../../legend)


---


| [getPlotArea]() | Represents the plot area of a chart. Read-only IChartPlotArea. |

### Result
[ChartPlotArea](../../chartplotarea)


---


| [getPlotVisibleCellsOnly]() | Determines whether the only visible cells are plotted. False to plot both visible and hidden cells. Read/write boolean. |

### Result
boolean


---


| [getRotation3D]() | Returns a 3D rotation of a chart. Read-only IRotation3D. |

### Result
[Rotation3D](../../rotation3d)


---


| [getShowDataLabelsOverMaximum]() | Specifies data labels over the maximum of the chart shall be shown. Read/write boolean. |

### Result
boolean


---


| [getSideWall]() | Returns an object which allows to change format of the side wall of a 3D chart. Read-only IChartWall. |

### Result
[ChartWall](../../chartwall)


---


| [getStyle]() | Returns or sets the chart style. Read/write StyleType. |

### Result
int


---


| [getTextFormat]() | Returns chart text format. The property is not applicable for the following types: ChartType#Treemap, ChartType#Sunburst, ChartType#Waterfall, ChartType#Histogram, ChartType#Funnel, ChartType#BoxAndWhisker. Read-only IChartTextFormat. |

### Result
[ChartTextFormat](../../charttextformat)


---


| [getThemeManager]() | Returns theme manager. Read-only IOverrideThemeManager. |

### Result
[NotesSlideThemeManager](../../notesslidethememanager), [ChartThemeManager](../../chartthememanager), [BaseOverrideThemeManager](../../baseoverridethememanager), [LayoutSlideThemeManager](../../layoutslidethememanager), [SlideThemeManager](../../slidethememanager)


---


| [getType]() | Returns or sets the chart type. Read/write ChartType. |

### Result
int


---


| [getUserShapes]() | Specify the shapes drawn on top of the chart. Read-only IGroupShape. |

### Result
[GroupShape](../../groupshape)


---


| [hasDataTable]() | Determines whether a chart has a data table. Read/write boolean. |

### Result
boolean


---


| [hasLegend]() | Determines whether a chart has a legend. Read/write boolean. |

### Result
boolean


---


| [hasRoundedCorners]() | Specifies the chart area shall have rounded corners. Read/write boolean. |

### Result
boolean


---


| [hasTitle]() | Determines whether a chart has a visible title. Read/write boolean. |

### Result
boolean


---


| [setDataTable](boolean) | Determines whether a chart has a data table. Read/write boolean. |


---


| [setDisplayBlanksAs](int) | Returns or sets the way to plot blank cells on a chart. Read/write DisplayBlanksAsType. |


---


| [setLegend](boolean) | Determines whether a chart has a legend. Read/write boolean. |


---


| [setPlotVisibleCellsOnly](boolean) | Determines whether the only visible cells are plotted. False to plot both visible and hidden cells. Read/write boolean. |


---


| [setRoundedCorners](boolean) | Specifies the chart area shall have rounded corners. Read/write boolean. |


---


| [setShowDataLabelsOverMaximum](boolean) | Specifies data labels over the maximum of the chart shall be shown. Read/write boolean. |


---


| [setStyle](int) | Returns or sets the chart style. Read/write StyleType. |


---


| [setTitle](boolean) | Determines whether a chart has a visible title. Read/write boolean. |


---


| [setType](int) | Returns or sets the chart type. Read/write ChartType. |


---


| [validateChartLayout]() | Calculates actual values of chart elements. The actual values include position of elements that implement IActualLayout interface (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) and actual axes values (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |


---



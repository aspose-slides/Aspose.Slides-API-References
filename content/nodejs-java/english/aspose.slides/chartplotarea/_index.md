---
title: ChartPlotArea
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/chartplotarea/
---

## ChartPlotArea class

 Represents rectangle where chart should be plotted.
 
| [getActualHeight] () Specifies actual height of the chart element. Call function IChart.ValidateChartLayout() before to get actual values. Read float. |

### Result
float


---


| [getActualWidth] () Specifies actual width of the chart element. Call function IChart.ValidateChartLayout() before to get actual values. Read float. |

### Result
float


---


| [getActualX] () Specifies actual x location (left) of the chart element relative to the left top corner of the chart. Call function IChart.ValidateChartLayout() before to get actual values. Read float. |

### Result
float


---


| [getActualY] () Specifies actual top of the chart element relative to the left top corner of the chart. Call function IChart.ValidateChartLayout() before to get actual values. Read float. |

### Result
float


---


| [getBottom] () Bottom. Read-only float. |

### Result
float


---


| [getChart] () Chart. Read-only IChart. |

### Result
[Chart]


---


| [getFormat] () Returns the format of a plot area. Read-only IFormat. |

### Result
[Format]


---


| [getHeight] () Returns or sets the height of a plot area bounding box as a fraction of the height of the chart (from 0 to 1). Read/write float. |

### Result
float


---


| [getLayoutTargetType] () If layout of the plot area defined manually this property specifies whether to layout the plot area by its inside (not including axis and axis labels) or outside (including axis and axis labels). Read/write LayoutTargetType( #getLayoutTargetType/ #setLayoutTargetType(int)). Presentation presentation = new Presentation(); try { ISlide slide = presentation.getSlides().get_Item(0); IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 20, 100, 600, 400); chart.getPlotArea().setX(0.2f); chart.getPlotArea().setY(0.2f); chart.getPlotArea().setWidth(0.7f); chart.getPlotArea().setHeight(0.7f); chart.getPlotArea().setLayoutTargetType(LayoutTargetType.Inner); ... } finally { if (presentation != null) presentation.dispose(); } |

### Result
int


---


| [getPresentation] () Returns the parent presentation of a FillFormat. Read-only IPresentation. |

### Result
[Presentation]


---


| [getRight] () Right. Read-only float. |

### Result
float


---


| [getSlide] () Returns the parent slide of a FillFormat. Read-only BaseSlide. |

### Result
[MasterNotesSlide], [MasterHandoutSlide], [BaseSlide], [NotesSlide], [LayoutSlide], [Slide], [MasterSlide]


---


| [getWidth] () Returns or sets the width of a plot area bounding box as a fraction of the width of the chart (from 0 to 1). Read/write float. |

### Result
float


---


| [getX] () Returns or sets the x coordinate of the upper left corner of plot area bounding box as a fraction of the width of the chart (from 0 to 1). Read/write float. |

### Result
float


---


| [getY] () Returns or sets the y coordinate of the upper left corner of plot area bounding box as a fraction of the height of the chart (from 0 to 1). Read/write float. |

### Result
float


---


| [isLocationAutocalculated] () Defines how location should be calculated: true – calculated automatically; defined by the X, Y, Width, Height properties. Read-only boolean. |

### Result
boolean


---


| [setHeight] ([float]) Returns or sets the height of a plot area bounding box as a fraction of the height of the chart (from 0 to 1). Read/write float. |


---


| [setLayoutTargetType] ([int]) If layout of the plot area defined manually this property specifies whether to layout the plot area by its inside (not including axis and axis labels) or outside (including axis and axis labels). Read/write LayoutTargetType( #getLayoutTargetType/ #setLayoutTargetType(int)). Presentation presentation = new Presentation(); try { ISlide slide = presentation.getSlides().get_Item(0); IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 20, 100, 600, 400); chart.getPlotArea().setX(0.2f); chart.getPlotArea().setY(0.2f); chart.getPlotArea().setWidth(0.7f); chart.getPlotArea().setHeight(0.7f); chart.getPlotArea().setLayoutTargetType(LayoutTargetType.Inner); ... } finally { if (presentation != null) presentation.dispose(); } |


---


| [setWidth] ([float]) Returns or sets the width of a plot area bounding box as a fraction of the width of the chart (from 0 to 1). Read/write float. |


---


| [setX] ([float]) Returns or sets the x coordinate of the upper left corner of plot area bounding box as a fraction of the width of the chart (from 0 to 1). Read/write float. |


---


| [setY] ([float]) Returns or sets the y coordinate of the upper left corner of plot area bounding box as a fraction of the height of the chart (from 0 to 1). Read/write float. |


---



---
title: ChartSeriesGroup
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/chartseriesgroup/
---

## ChartSeriesGroup class

 Represents group of series.
 
 1) See summary and remarks for ChartSeriesGroupCollection class and CombinableSeriesTypesGroup enum.
 2) Group of series contains some series properies whitch is common for 
 each series in group ("series group properties").
 "Series group properties" in ChartSeriesGroup class is read/write.
 Each of "series group properties" can have a read-only projection in ChartSeries class.
 

## Functions

| Name | Description |
| --- | --- |
| [getBubbleSizeRepresentation]() | Specifies how the bubble size values are represented on the bubble chart. Read/write BubbleSizeRepresentationType. |

### Result
int


---


| [getBubbleSizeScale]() | Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). Read/write int. |

### Result
int


---


| [getChart]() | Returns the parent chart. Read-only IChart. |

### Result
[Chart](../../chart)


---


| [getDoughnutHoleSize]() | Specifies the size of the hole in a doughnut chart (can be between 0 and 90 percents of the size of the plot area.). Read/write byte. |

### Result
byte


---


| [getFirstSliceAngle]() | Gets or sets the angle of the first pie or doughnut chart slice, in degrees (clockwise from up, from 0 to 360 degrees). Read/write int. |

### Result
int


---


| [getGapDepth]() | Returns or sets the distance, as a percentage of the marker width, between the data series in a 3D chart. Read/write int. |

### Result
int


---


| [getGapWidth]() | Specifies the space between bar or column clusters, as a percentage of the bar or column width. Read/write int. |

### Result
int


---


| [getHiLowLinesFormat]() | Specifies HiLowLines format. HiLowLines applied with HiLowClose, OpenHiLowClose, VolumeHiLowClose and VolumeOpenHiLowClose chart types. |

### Result
[ChartLinesFormat](../../chartlinesformat)


---


| [getOverlap]() | Specifies how much bars and columns shall overlap on 2-D charts (from -100 to 100). Read/write byte. |

### Result
byte


---


| [getPieSplitBy]() | Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Read/write PieSplitType. |

### Result
int


---


| [getPieSplitCustomPoints]() | The custom split information for a pie-of-pie or bar-of-pie chart with a custom split. Contains data points that shall be drawn in the second pie or bar in a pie-of-pie or bar-of-pie chart. Read-only PieSplitCustomPointCollection. |

### Result
[PieSplitCustomPointCollection](../../piesplitcustompointcollection)


---


| [getPieSplitPosition]() | Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Is used together with PieSplitBy property. Read/write double. |

### Result
double


---


| [getPlotOnSecondAxis]() | Indicates if series of this group is plotted on secondary axis. Read-only boolean. |

### Result
boolean


---


| [getPresentation]() | Returns the parent presentation of a FillFormat. Read-only IPresentation. |

### Result
[Presentation](../../presentation)


---


| [getSecondPieSize]() | Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). Read/write int. |

### Result
int


---


| [getSeries]() | Returns a collection of series. Read-only IChartSeriesReadonlyCollection. |

### Result
ChartSeriesReadonlyCollection


---


| [getSlide]() | Returns the parent slide of a FillFormat. Read-only BaseSlide. |

### Result
[MasterNotesSlide](../../masternotesslide), [MasterHandoutSlide](../../masterhandoutslide), [BaseSlide](../../baseslide), [NotesSlide](../../notesslide), [LayoutSlide](../../layoutslide), [Slide](../../slide), [MasterSlide](../../masterslide)


---


| [getType]() | Returns a type of this series group. Read-only CombinableSeriesTypesGroup. |

### Result
int


---


| [getUpDownBars]() | Provede access to up/down bars of Line- or Stock-chart. Read-only IUpDownBarsManager. |

### Result
[UpDownBarsManager](../../updownbarsmanager)


---


| [get_Item](int) | Gets the element at the specified index. |

### Result
[ChartSeries](../../chartseries)


---


| [hasSeriesLines]() | True if chart has series lines. Applied to stacked bar and OfPie charts. Read/write boolean. |

### Result
boolean


---


| [isColorVaried]() | Specifies that each data marker in the series has a different color. Read/write boolean. |

### Result
boolean


---


| [setBubbleSizeRepresentation](int) | Specifies how the bubble size values are represented on the bubble chart. Read/write BubbleSizeRepresentationType. |


---


| [setBubbleSizeScale](int) | Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). Read/write int. |


---


| [setColorVaried](boolean) | Specifies that each data marker in the series has a different color. Read/write boolean. |


---


| [setDoughnutHoleSize](byte) | Specifies the size of the hole in a doughnut chart (can be between 0 and 90 percents of the size of the plot area.). Read/write byte. |


---


| [setFirstSliceAngle](int) | Gets or sets the angle of the first pie or doughnut chart slice, in degrees (clockwise from up, from 0 to 360 degrees). Read/write int. |


---


| [setGapDepth](int) | Returns or sets the distance, as a percentage of the marker width, between the data series in a 3D chart. Read/write int. |


---


| [setGapWidth](int) | Specifies the space between bar or column clusters, as a percentage of the bar or column width. Read/write int. |


---


| [setOverlap](byte) | Specifies how much bars and columns shall overlap on 2-D charts (from -100 to 100). Read/write byte. |


---


| [setPieSplitBy](int) | Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Read/write PieSplitType. |


---


| [setPieSplitPosition](double) | Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Is used together with PieSplitBy property. Read/write double. |


---


| [setSecondPieSize](int) | Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). Read/write int. |


---


| [setSeriesLines](boolean) | True if chart has series lines. Applied to stacked bar and OfPie charts. Read/write boolean. |


---



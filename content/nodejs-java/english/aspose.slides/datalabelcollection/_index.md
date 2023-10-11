---
title: DataLabelCollection
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/datalabelcollection/
---

## DataLabelCollection class

 Represents a series labels.
 
| [getChart] () Returns the parent chart. Read-only IChart. |

### Result
[Chart]


---


| [getCount] () Gets the number of all data labels in the collection. Read-only int. |

### Result
int


---


| [getCountOfVisibleDataLabels] () Gets the number of visible data labels in the collection. Read-only int. |

### Result
int


---


| [getDefaultDataLabelFormat] () Gets the default data label format. Read-only IDataLabelFormat. |

### Result
[DataLabelFormat]


---


| [getLeaderLinesColor] () Gets or sets the color of all leader lines in the collection. Read/write java.awt.Color. |

### Result
Color


---


| [getLeaderLinesFormat] () Represents data labels leader lines format. Read-only IChartLinesFormat. |

### Result
[ChartLinesFormat]


---


| [getParentSeries] () Gets the parent series. Read-only IChartSeries. |

### Result
[ChartSeries]


---


| [getPresentation] () Returns the parent presentation of a FillFormat. Read-only IPresentation. |

### Result
[Presentation]


---


| [getSlide] () Returns the parent slide of a FillFormat. Read-only BaseSlide. |

### Result
[MasterNotesSlide], [MasterHandoutSlide], [BaseSlide], [NotesSlide], [LayoutSlide], [Slide], [MasterSlide]


---


| [get_Item] ([int]) Gets the data label for the data point with the specified index. Alternate way to access data label is: - series.getDataPoints().get_Item(i).getLabel() - manage label properties. |

### Result
[DataLabel]


---


| [hide] () Make data label hidden by default by setting all Show*-flags (ShowValue, ...) of the DefaultDataLabelFormat property to false state. IsVisible will be false after this. If data label is not visible by default (IsVisible is false) you can make data label "visible by default" with setting Show*-flags (ShowValue, ...) of the DefaultDataLabelFormat property to true state. |


---


| [indexOf] ([DataLabel]) Returns an index of the specified DataLabel in the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| value | [DataLabel] | DataLabel to find. |

### Result
int


---


| [isVisible] () False means that data label is not visible by default (and so all Show*-flags (ShowValue, ...) of the DefaultDataLabelFormat property are false). Read-only boolean. If data label is visible by default you can make it hidden by default with Hide() function. But if data label is not visible by default (IsVisible is false) you can make data label "visible by default" with setting Show*-flags (ShowValue, ...) of the DefaultDataLabelFormat property to true state. |

### Result
boolean


---


| [iterator] () Returns an enumerator that iterates through the collection. |

### Result



---


| [iteratorJava] () Returns a java iterator for the entire collection. |

### Result



---


| [setLeaderLinesColor] ([Color]) Gets or sets the color of all leader lines in the collection. Read/write java.awt.Color. |


---



---
title: DataLabel
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/datalabel/
---

## DataLabel class

 Represents a series labels.
 
| [DataLabel]([ChartDataPoint]) | Creates a new instance of DataLabel class. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| parentImmediate | [ChartDataPoint] | Parent ChartDataPoint. |

### Result
DataLabel


---


| [addTextFrameForOverriding] ([String]) | Initialize TextFrameForOverriding with the text in paramener "text". If TextFrameForOverriding is already initialized then simply changes its text. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| text | [String] | Text for a new TextFrameForOverriding. |

### Result
[TextFrame]


---


| [getActualHeight] () | Specifies actual height of the chart element. Call function IChart.ValidateChartLayout() before to get actual values. Read float. |

### Result
float


---


| [getActualLabelText] () | Returns actual label text based on DataLabelFormat settings or TextFrameForOverriding.Text value. |

### Result
String


---


| [getActualWidth] () | Specifies actual width of the chart element. Call function IChart.ValidateChartLayout() before to get actual values. Read float. |

### Result
float


---


| [getActualX] () | Specifies actual x location (left) of the chart element relative to the left top corner of the chart. Call function IChart.ValidateChartLayout() before to get actual values. Read float. |

### Result
float


---


| [getActualY] () | Specifies actual top of the chart element relative to the left top corner of the chart. Call function IChart.ValidateChartLayout() before to get actual values. Read float. |

### Result
float


---


| [getBottom] () | Bottom. Read-only float. |

### Result
float


---


| [getChart] () | Returns the parent chart. Read-only IChart. |

### Result
[Chart]


---


| [getDataLabelFormat] () | Returns data label format. Read-only IDataLabelFormat. |

### Result
[DataLabelFormat]


---


| [getHeight] () | Returns or sets the height of a title as a fraction of the height of the chart. Read/write float. |

### Result
float


---


| [getPresentation] () | Returns the parent presentation of a FillFormat. Read-only IPresentation. |

### Result
[Presentation]


---


| [getRight] () | Right. Read-only float. |

### Result
float


---


| [getSlide] () | Returns the parent slide of a FillFormat. Read-only BaseSlide. |

### Result
[MasterNotesSlide], [MasterHandoutSlide], [BaseSlide], [NotesSlide], [LayoutSlide], [Slide], [MasterSlide]


---


| [getTextFormat] () | Returns text format. Read-only IChartTextFormat. |

### Result
[ChartTextFormat]


---


| [getTextFrameForOverriding] () | Can contain a rich formatted text. If this property is not null then this formatted text value overrides auto-generated text of data label. Auto-generated text of data label means text that is managed by ShowSeriesName, ShowValue, ... properties and is formatted with the TextFormatManager.TextFormat property. Read-only ITextFrame. |

### Result
[TextFrame]


---


| [getValueFromCell] () | Gets or sets workbook data cell. Applied if IDataLabelFormat.ShowLabelValueFromCell property equals true. |

### Result
[ChartDataCell]


---


| [getWidth] () | Returns or sets the width of a title as a fraction of the width of the chart. Read/write float. |

### Result
float


---


| [getX] () | Returns or sets the x coordinate of a title as a fraction of the width of the chart. Read/write float. |

### Result
float


---


| [getY] () | Returns or sets the y coordinate of a title as a fraction of the height of the chart. Read/write float. |

### Result
float


---


| [hide] () | Make data label hidden by setting all Show*-flags (ShowValue, ...) to false state. IsVisible will be false after this. If data label is not visible (IsVisible is false) you can make data label visible with setting Show*-flags (ShowValue, ...) to true state. |


---


| [isVisible] () | False means that data label is not visible (and so all Show*-flags (ShowValue, ...) are false). Read-only boolean. If data label is visible you can make it hidden with Hide() function. But if data label is not visible (IsVisible is false) you can make data label visible with setting Show*-flags (ShowValue, ...) to true state. |

### Result
boolean


---


| [setHeight] ([float]) | Returns or sets the height of a title as a fraction of the height of the chart. Read/write float. |


---


| [setValueFromCell] ([ChartDataCell]) | Gets or sets workbook data cell. Applied if IDataLabelFormat.ShowLabelValueFromCell property equals true. |


---


| [setWidth] ([float]) | Returns or sets the width of a title as a fraction of the width of the chart. Read/write float. |


---


| [setX] ([float]) | Returns or sets the x coordinate of a title as a fraction of the width of the chart. Read/write float. |


---


| [setY] ([float]) | Returns or sets the y coordinate of a title as a fraction of the height of the chart. Read/write float. |


---



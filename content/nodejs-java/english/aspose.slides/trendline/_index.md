---
title: Trendline
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/trendline/
---

## Trendline class

 Class represents trend line of chart series
 
| [addTextFrameForOverriding] ([String]) Initialize TextFrameForOverriding with the text in paramener "text". If TextFrameForOverriding is already initialized then simply changes its text. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| text | [String] | Text for a new TextFrameForOverriding. |

### Result
[TextFrame]


---


| [getBackward] () Specifies the number of categories (or units on a scatter chart) that the trend line extends before the data for the series that is being trended. On scatter and non-scatter charts, the value shall be any nonnegative value. Read/write double. |

### Result
double


---


| [getChart] () Returns the parent chart. Read-only IChart. |

### Result
[Chart]


---


| [getDisplayEquation] () Specifies that the equation for the trendline is displayed on the chart (in the same label as the Rsquaredvalue). Read/write boolean. |

### Result
boolean


---


| [getDisplayRSquaredValue] () Specifies that the R-squared value of the trendline is displayed on the chart (in the same label as the equation). Read/write boolean. |

### Result
boolean


---


| [getFormat] () Represents the format of the trend line. Read/write IFormat. |

### Result
[Format]


---


| [getForward] () Specifies the number of categories (or units on a scatter chart) that the trendline extends after the data for the series that is being trended. On scatter and non-scatter charts, the value shall be any non-negative value. Read/write double. |

### Result
double


---


| [getIntercept] () Specifies the value where the trendline shall cross the y axis. This property shall be supported only when the trendline type is exp, linear, or poly. Read/write double. |

### Result
double


---


| [getOrder] () Specifies the order of the polynomial trend line. It is ignored for other trend line types. Value must be between 2 and 6. Read/write byte. |

### Result
byte


---


| [getPeriod] () Specifies the period of the trend line for a moving average trend line. It is ignored for other trend line variants. Value must be between 2 and 255. Read/write byte. |

### Result
byte


---


| [getPresentation] () Returns the parent presentation of a FillFormat. Read-only IPresentation. |

### Result
[Presentation]


---


| [getRelatedLegendEntry] () Represents legend entry related with this trendline Read-only ILegendEntryProperties. |

### Result
[LegendEntryProperties]


---


| [getSlide] () Returns the parent slide of a FillFormat. Read-only BaseSlide. |

### Result
[MasterNotesSlide], [MasterHandoutSlide], [BaseSlide], [NotesSlide], [LayoutSlide], [Slide], [MasterSlide]


---


| [getTextFormat] () Returns text format. Read-only IChartTextFormat. |

### Result
[ChartTextFormat]


---


| [getTextFrameForOverriding] () Can contain a rich formatted text. If this property is not null then this formatted text value overrides auto-generated text of data label. Auto-generated text of data label means text that is managed by ShowSeriesName, ShowValue, ... properties and is formatted with the TextFormatManager.TextFormat property. Read-only ITextFrame. |

### Result
[TextFrame]


---


| [getTrendlineName] () Gets or sets name of the trendline. Read/write String. |

### Result
String


---


| [getTrendlineType] () Gets or sets type of trend line. Read/write TrendlineType. |

### Result
int


---


| [setBackward] ([double]) Specifies the number of categories (or units on a scatter chart) that the trend line extends before the data for the series that is being trended. On scatter and non-scatter charts, the value shall be any nonnegative value. Read/write double. |


---


| [setDisplayEquation] ([boolean]) Specifies that the equation for the trendline is displayed on the chart (in the same label as the Rsquaredvalue). Read/write boolean. |


---


| [setDisplayRSquaredValue] ([boolean]) Specifies that the R-squared value of the trendline is displayed on the chart (in the same label as the equation). Read/write boolean. |


---


| [setFormat] ([Format]) Represents the format of the trend line. Read/write IFormat. |


---


| [setForward] ([double]) Specifies the number of categories (or units on a scatter chart) that the trendline extends after the data for the series that is being trended. On scatter and non-scatter charts, the value shall be any non-negative value. Read/write double. |


---


| [setIntercept] ([double]) Specifies the value where the trendline shall cross the y axis. This property shall be supported only when the trendline type is exp, linear, or poly. Read/write double. |


---


| [setOrder] ([byte]) Specifies the order of the polynomial trend line. It is ignored for other trend line types. Value must be between 2 and 6. Read/write byte. |


---


| [setPeriod] ([byte]) Specifies the period of the trend line for a moving average trend line. It is ignored for other trend line variants. Value must be between 2 and 255. Read/write byte. |


---


| [setTrendlineName] ([String]) Gets or sets name of the trendline. Read/write String. |


---


| [setTrendlineType] ([int]) Gets or sets type of trend line. Read/write TrendlineType. |


---



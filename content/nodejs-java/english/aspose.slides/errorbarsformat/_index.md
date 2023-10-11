---
title: ErrorBarsFormat
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/errorbarsformat/
---

## ErrorBarsFormat class

 Represents error bars of chart series. ErrorBars custom values are in IChartDataPointCollection
 (in ( IChartDataPoint#getErrorBarsCustomValues) property).
 
| [getChart] () Returns the parent chart. Read-only IChart. |

### Result
[Chart]


---


| [getFormat] () Represents the format of the error bars. Read/write IFormat. |

### Result
[Format]


---


| [getPresentation] () Returns the parent presentation of a FillFormat. Read-only IPresentation. |

### Result
[Presentation]


---


| [getSlide] () Returns the parent slide of a FillFormat. Read-only BaseSlide. |

### Result
[MasterNotesSlide], [MasterHandoutSlide], [BaseSlide], [NotesSlide], [LayoutSlide], [Slide], [MasterSlide]


---


| [getType] () Gets or sets type of error bars. Read/write ErrorBarType. |

### Result
int


---


| [getValue] () Gets or sets value which is used with Fixed, Percentage and StandardDeviation value types to determine the length of the error bars. In any other case will return NaN. Read/write float. |

### Result
float


---


| [getValueType] () Represents possible ways to determine the length of the error bars. In case of custom value type to specify value use ( IChartDataPoint#getErrorBarsCustomValues) property of specific data point in DataPoints collection of series. In case of Fixed, Percentage or StandardDeviation value type use Value property to specify value. Read/write ErrorBarValueType. |

### Result
int


---


| [hasEndCap] () Specifies an end cap is not drawn on the error bars. Read/write boolean. |

### Result
boolean


---


| [isVisible] () Gets or sets Error Bars visibility . Read/write boolean. |

### Result
boolean


---


| [setEndCap] ([boolean]) Specifies an end cap is not drawn on the error bars. Read/write boolean. |


---


| [setFormat] ([Format]) Represents the format of the error bars. Read/write IFormat. |


---


| [setType] ([int]) Gets or sets type of error bars. Read/write ErrorBarType. |


---


| [setValue] ([float]) Gets or sets value which is used with Fixed, Percentage and StandardDeviation value types to determine the length of the error bars. In any other case will return NaN. Read/write float. |


---


| [setValueType] ([int]) Represents possible ways to determine the length of the error bars. In case of custom value type to specify value use ( IChartDataPoint#getErrorBarsCustomValues) property of specific data point in DataPoints collection of series. In case of Fixed, Percentage or StandardDeviation value type use Value property to specify value. Read/write ErrorBarValueType. |


---


| [setVisible] ([boolean]) Gets or sets Error Bars visibility . Read/write boolean. |


---



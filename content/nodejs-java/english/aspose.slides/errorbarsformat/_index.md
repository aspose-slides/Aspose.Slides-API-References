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
 
| Name | Description |
| --- | --- |
| getChart () | Returns the parent chart. Read-only IChart. |

### Result
Chart(../../chart)


---


| Name | Description |
| --- | --- |
| getFormat () | Represents the format of the error bars. Read/write IFormat. |

### Result
Format(../../format)


---


| Name | Description |
| --- | --- |
| getPresentation () | Returns the parent presentation of a FillFormat. Read-only IPresentation. |

### Result
Presentation(../../presentation)


---


| Name | Description |
| --- | --- |
| getSlide () | Returns the parent slide of a FillFormat. Read-only BaseSlide. |

### Result
MasterNotesSlide(../../masternotesslide), MasterHandoutSlide(../../masterhandoutslide), BaseSlide(../../baseslide), NotesSlide(../../notesslide), LayoutSlide(../../layoutslide), Slide(../../slide), MasterSlide(../../masterslide)


---


| Name | Description |
| --- | --- |
| getType () | Gets or sets type of error bars. Read/write ErrorBarType. |

### Result
int


---


| Name | Description |
| --- | --- |
| getValue () | Gets or sets value which is used with Fixed, Percentage and StandardDeviation value types to determine the length of the error bars. In any other case will return NaN. Read/write float. |

### Result
float


---


| Name | Description |
| --- | --- |
| getValueType () | Represents possible ways to determine the length of the error bars. In case of custom value type to specify value use ( IChartDataPoint#getErrorBarsCustomValues) property of specific data point in DataPoints collection of series. In case of Fixed, Percentage or StandardDeviation value type use Value property to specify value. Read/write ErrorBarValueType. |

### Result
int


---


| Name | Description |
| --- | --- |
| hasEndCap () | Specifies an end cap is not drawn on the error bars. Read/write boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| isVisible () | Gets or sets Error Bars visibility . Read/write boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| setEndCap (boolean) | Specifies an end cap is not drawn on the error bars. Read/write boolean. |


---


| Name | Description |
| --- | --- |
| setFormat (Format(../format)) | Represents the format of the error bars. Read/write IFormat. |


---


| Name | Description |
| --- | --- |
| setType (int) | Gets or sets type of error bars. Read/write ErrorBarType. |


---


| Name | Description |
| --- | --- |
| setValue (float) | Gets or sets value which is used with Fixed, Percentage and StandardDeviation value types to determine the length of the error bars. In any other case will return NaN. Read/write float. |


---


| Name | Description |
| --- | --- |
| setValueType (int) | Represents possible ways to determine the length of the error bars. In case of custom value type to specify value use ( IChartDataPoint#getErrorBarsCustomValues) property of specific data point in DataPoints collection of series. In case of Fixed, Percentage or StandardDeviation value type use Value property to specify value. Read/write ErrorBarValueType. |


---


| Name | Description |
| --- | --- |
| setVisible (boolean) | Gets or sets Error Bars visibility . Read/write boolean. |


---



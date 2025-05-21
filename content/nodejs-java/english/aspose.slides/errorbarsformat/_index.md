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
 
### getChart {#getChart}

| Name | Description |
| --- | --- |
| getChart () | Returns the parent chart. Read-only IChart. |

 **Returns:**
[Chart](../chart)


---


### getFormat {#getFormat}

| Name | Description |
| --- | --- |
| getFormat () | Represents the format of the error bars. Read/write IFormat. |

 **Returns:**
[Format](../format)


---


### getPresentation {#getPresentation}

| Name | Description |
| --- | --- |
| getPresentation () | Returns the parent presentation of a FillFormat. Read-only IPresentation. |

 **Returns:**
[Presentation](../presentation)


---


### getSlide {#getSlide}

| Name | Description |
| --- | --- |
| getSlide () | Returns the parent slide of a FillFormat. Read-only BaseSlide. |

 **Returns:**
[LayoutSlide](../layoutslide), [Slide](../slide), [NotesSlide](../notesslide), [BaseSlide](../baseslide), [MasterNotesSlide](../masternotesslide), [MasterHandoutSlide](../masterhandoutslide), [MasterSlide](../masterslide)


---


### getType {#getType}

| Name | Description |
| --- | --- |
| getType () | Gets or sets type of error bars. Read/write ErrorBarType. |

 **Returns:**
int


---


### getValue {#getValue}

| Name | Description |
| --- | --- |
| getValue () | Gets or sets value which is used with Fixed, Percentage and StandardDeviation value types to determine the length of the error bars. In any other case will return NaN. Read/write float. |

 **Returns:**
float


---


### getValueType {#getValueType}

| Name | Description |
| --- | --- |
| getValueType () | Represents possible ways to determine the length of the error bars. In case of custom value type to specify value use ( IChartDataPoint#getErrorBarsCustomValues) property of specific data point in DataPoints collection of series. In case of Fixed, Percentage or StandardDeviation value type use Value property to specify value. Read/write ErrorBarValueType. |

 **Returns:**
int


---


### hasEndCap {#hasEndCap}

| Name | Description |
| --- | --- |
| hasEndCap () | Specifies an end cap is not drawn on the error bars. Read/write boolean. |

 **Returns:**
boolean


---


### isVisible {#isVisible}

| Name | Description |
| --- | --- |
| isVisible () | Gets or sets Error Bars visibility . Read/write boolean. |

 **Returns:**
boolean


---


### setEndCap {#setEndCap}

| Name | Description |
| --- | --- |
| setEndCap (boolean) | Specifies an end cap is not drawn on the error bars. Read/write boolean. |


---


### setFormat {#setFormat}

| Name | Description |
| --- | --- |
| setFormat ([Format](../format)) | Represents the format of the error bars. Read/write IFormat. |


---


### setType {#setType}

| Name | Description |
| --- | --- |
| setType (int) | Gets or sets type of error bars. Read/write ErrorBarType. |


---


### setValue {#setValue}

| Name | Description |
| --- | --- |
| setValue (float) | Gets or sets value which is used with Fixed, Percentage and StandardDeviation value types to determine the length of the error bars. In any other case will return NaN. Read/write float. |


---


### setValueType {#setValueType}

| Name | Description |
| --- | --- |
| setValueType (int) | Represents possible ways to determine the length of the error bars. In case of custom value type to specify value use ( IChartDataPoint#getErrorBarsCustomValues) property of specific data point in DataPoints collection of series. In case of Fixed, Percentage or StandardDeviation value type use Value property to specify value. Read/write ErrorBarValueType. |


---


### setVisible {#setVisible}

| Name | Description |
| --- | --- |
| setVisible (boolean) | Gets or sets Error Bars visibility . Read/write boolean. |


---



---
title: DataLabel
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/datalabel/
---

## DataLabel class

 Represents a series labels.
 
### DataLabel {#DataLabel}

| Name | Description |
| --- | --- |
| DataLabel([ChartDataPoint](../chartdatapoint)) | Creates a new instance of DataLabel class. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| parentImmediate | [ChartDataPoint](../chartdatapoint) | Parent ChartDataPoint. |

 **Result:**
DataLabel


---


### addTextFrameForOverriding {#addTextFrameForOverriding}

| Name | Description |
| --- | --- |
| addTextFrameForOverriding (String) | Initialize TextFrameForOverriding with the text in paramener "text". If TextFrameForOverriding is already initialized then simply changes its text. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| text | String | Text for a new TextFrameForOverriding. |

 **Result:**
[TextFrame](../textframe)


---


### getActualHeight {#getActualHeight}

| Name | Description |
| --- | --- |
| getActualHeight () | Specifies actual height of the chart element. Call method IChart.ValidateChartLayout() before to get actual values. Read float. |

 **Result:**
float


---


### getActualLabelText {#getActualLabelText}

| Name | Description |
| --- | --- |
| getActualLabelText () | Returns actual label text based on DataLabelFormat settings or TextFrameForOverriding.Text value. |

 **Result:**
String


---


### getActualWidth {#getActualWidth}

| Name | Description |
| --- | --- |
| getActualWidth () | Specifies actual width of the chart element. Call method IChart.ValidateChartLayout() before to get actual values. Read float. |

 **Result:**
float


---


### getActualX {#getActualX}

| Name | Description |
| --- | --- |
| getActualX () | Specifies actual x location (left) of the chart element relative to the left top corner of the chart. Call method IChart.ValidateChartLayout() before to get actual values. Read float. |

 **Result:**
float


---


### getActualY {#getActualY}

| Name | Description |
| --- | --- |
| getActualY () | Specifies actual top of the chart element relative to the left top corner of the chart. Call method IChart.ValidateChartLayout() before to get actual values. Read float. |

 **Result:**
float


---


### getBottom {#getBottom}

| Name | Description |
| --- | --- |
| getBottom () | Bottom. Read-only float. |

 **Result:**
float


---


### getChart {#getChart}

| Name | Description |
| --- | --- |
| getChart () | Returns the parent chart. Read-only IChart. |

 **Result:**
[Chart](../chart)


---


### getDataLabelFormat {#getDataLabelFormat}

| Name | Description |
| --- | --- |
| getDataLabelFormat () | Returns data label format. Read-only IDataLabelFormat. |

 **Result:**
[DataLabelFormat](../datalabelformat)


---


### getHeight {#getHeight}

| Name | Description |
| --- | --- |
| getHeight () | Returns or sets the height of a title as a fraction of the height of the chart. Read/write float. |

 **Result:**
float


---


### getPresentation {#getPresentation}

| Name | Description |
| --- | --- |
| getPresentation () | Returns the parent presentation of a FillFormat. Read-only IPresentation. |

 **Result:**
[Presentation](../presentation)


---


### getRight {#getRight}

| Name | Description |
| --- | --- |
| getRight () | Right. Read-only float. |

 **Result:**
float


---


### getSlide {#getSlide}

| Name | Description |
| --- | --- |
| getSlide () | Returns the parent slide of a FillFormat. Read-only BaseSlide. |

 **Result:**
[Slide](../slide), [MasterNotesSlide](../masternotesslide), [BaseSlide](../baseslide), [MasterSlide](../masterslide), [LayoutSlide](../layoutslide), [MasterHandoutSlide](../masterhandoutslide), [NotesSlide](../notesslide)


---


### getTextFormat {#getTextFormat}

| Name | Description |
| --- | --- |
| getTextFormat () | Returns text format. Read-only IChartTextFormat. |

 **Result:**
[ChartTextFormat](../charttextformat)


---


### getTextFrameForOverriding {#getTextFrameForOverriding}

| Name | Description |
| --- | --- |
| getTextFrameForOverriding () | Can contain a rich formatted text. If this property is not null then this formatted text value overrides auto-generated text of data label. Auto-generated text of data label means text that is managed by ShowSeriesName, ShowValue, ... properties and is formatted with the TextFormatManager.TextFormat property. Read-only ITextFrame. |

 **Result:**
[TextFrame](../textframe)


---


### getValueFromCell {#getValueFromCell}

| Name | Description |
| --- | --- |
| getValueFromCell () | Gets or sets workbook data cell. Applied if IDataLabelFormat.ShowLabelValueFromCell property equals true. |

 **Result:**
[ChartDataCell](../chartdatacell)


---


### getWidth {#getWidth}

| Name | Description |
| --- | --- |
| getWidth () | Returns or sets the width of a title as a fraction of the width of the chart. Read/write float. |

 **Result:**
float


---


### getX {#getX}

| Name | Description |
| --- | --- |
| getX () | Returns or sets the x coordinate of a title as a fraction of the width of the chart. Read/write float. |

 **Result:**
float


---


### getY {#getY}

| Name | Description |
| --- | --- |
| getY () | Returns or sets the y coordinate of a title as a fraction of the height of the chart. Read/write float. |

 **Result:**
float


---


### hide {#hide}

| Name | Description |
| --- | --- |
| hide () | Make data label hidden by setting all Show*-flags (ShowValue, ...) to false state. IsVisible will be false after this. If data label is not visible (IsVisible is false) you can make data label visible with setting Show*-flags (ShowValue, ...) to true state. |


---


### isVisible {#isVisible}

| Name | Description |
| --- | --- |
| isVisible () | False means that data label is not visible (and so all Show*-flags (ShowValue, ...) are false). Read-only boolean. If data label is visible you can make it hidden with Hide() method. But if data label is not visible (IsVisible is false) you can make data label visible with setting Show*-flags (ShowValue, ...) to true state. |

 **Result:**
boolean


---


### setHeight {#setHeight}

| Name | Description |
| --- | --- |
| setHeight (float) | Returns or sets the height of a title as a fraction of the height of the chart. Read/write float. |


---


### setValueFromCell {#setValueFromCell}

| Name | Description |
| --- | --- |
| setValueFromCell ([ChartDataCell](../chartdatacell)) | Gets or sets workbook data cell. Applied if IDataLabelFormat.ShowLabelValueFromCell property equals true. |


---


### setWidth {#setWidth}

| Name | Description |
| --- | --- |
| setWidth (float) | Returns or sets the width of a title as a fraction of the width of the chart. Read/write float. |


---


### setX {#setX}

| Name | Description |
| --- | --- |
| setX (float) | Returns or sets the x coordinate of a title as a fraction of the width of the chart. Read/write float. |


---


### setY {#setY}

| Name | Description |
| --- | --- |
| setY (float) | Returns or sets the y coordinate of a title as a fraction of the height of the chart. Read/write float. |


---



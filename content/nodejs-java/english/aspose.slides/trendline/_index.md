---
title: Trendline
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/trendline/
---

## Trendline class

 Class represents trend line of chart series
 
### addTextFrameForOverriding {#addTextFrameForOverriding}

| Name | Description |
| --- | --- |
| addTextFrameForOverriding (String) | Initialize TextFrameForOverriding with the text in paramener "text". If TextFrameForOverriding is already initialized then simply changes its text. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| text | String | Text for a new TextFrameForOverriding. |

 **Returns:**
[TextFrame](../textframe)


---


### getBackward {#getBackward}

| Name | Description |
| --- | --- |
| getBackward () | Specifies the number of categories (or units on a scatter chart) that the trend line extends before the data for the series that is being trended. On scatter and non-scatter charts, the value shall be any nonnegative value. Read/write double. |

 **Returns:**
double


---


### getChart {#getChart}

| Name | Description |
| --- | --- |
| getChart () | Returns the parent chart. Read-only IChart. |

 **Returns:**
[Chart](../chart)


---


### getDisplayEquation {#getDisplayEquation}

| Name | Description |
| --- | --- |
| getDisplayEquation () | Specifies that the equation for the trendline is displayed on the chart (in the same label as the Rsquaredvalue). Read/write boolean. |

 **Returns:**
boolean


---


### getDisplayRSquaredValue {#getDisplayRSquaredValue}

| Name | Description |
| --- | --- |
| getDisplayRSquaredValue () | Specifies that the R-squared value of the trendline is displayed on the chart (in the same label as the equation). Read/write boolean. |

 **Returns:**
boolean


---


### getFormat {#getFormat}

| Name | Description |
| --- | --- |
| getFormat () | Represents the format of the trend line. Read/write IFormat. |

 **Returns:**
[Format](../format)


---


### getForward {#getForward}

| Name | Description |
| --- | --- |
| getForward () | Specifies the number of categories (or units on a scatter chart) that the trendline extends after the data for the series that is being trended. On scatter and non-scatter charts, the value shall be any non-negative value. Read/write double. |

 **Returns:**
double


---


### getIntercept {#getIntercept}

| Name | Description |
| --- | --- |
| getIntercept () | Specifies the value where the trendline shall cross the y axis. This property shall be supported only when the trendline type is exp, linear, or poly. Read/write double. |

 **Returns:**
double


---


### getOrder {#getOrder}

| Name | Description |
| --- | --- |
| getOrder () | Specifies the order of the polynomial trend line. It is ignored for other trend line types. Value must be between 2 and 6. Read/write byte. |

 **Returns:**
byte


---


### getPeriod {#getPeriod}

| Name | Description |
| --- | --- |
| getPeriod () | Specifies the period of the trend line for a moving average trend line. It is ignored for other trend line variants. Value must be between 2 and 255. Read/write byte. |

 **Returns:**
byte


---


### getPresentation {#getPresentation}

| Name | Description |
| --- | --- |
| getPresentation () | Returns the parent presentation of a FillFormat. Read-only IPresentation. |

 **Returns:**
[Presentation](../presentation)


---


### getRelatedLegendEntry {#getRelatedLegendEntry}

| Name | Description |
| --- | --- |
| getRelatedLegendEntry () | Represents legend entry related with this trendline Read-only ILegendEntryProperties. |

 **Returns:**
[LegendEntryProperties](../legendentryproperties)


---


### getSlide {#getSlide}

| Name | Description |
| --- | --- |
| getSlide () | Returns the parent slide of a FillFormat. Read-only BaseSlide. |

 **Returns:**
[Slide](../slide), [NotesSlide](../notesslide), [MasterHandoutSlide](../masterhandoutslide), [LayoutSlide](../layoutslide), [MasterNotesSlide](../masternotesslide), [BaseSlide](../baseslide), [MasterSlide](../masterslide)


---


### getTextFormat {#getTextFormat}

| Name | Description |
| --- | --- |
| getTextFormat () | Returns text format. Read-only IChartTextFormat. |

 **Returns:**
[ChartTextFormat](../charttextformat)


---


### getTextFrameForOverriding {#getTextFrameForOverriding}

| Name | Description |
| --- | --- |
| getTextFrameForOverriding () | Can contain a rich formatted text. If this property is not null then this formatted text value overrides auto-generated text of data label. Auto-generated text of data label means text that is managed by ShowSeriesName, ShowValue, ... properties and is formatted with the TextFormatManager.TextFormat property. Read-only ITextFrame. |

 **Returns:**
[TextFrame](../textframe)


---


### getTrendlineName {#getTrendlineName}

| Name | Description |
| --- | --- |
| getTrendlineName () | Gets or sets name of the trendline. Read/write String. |

 **Returns:**
String


---


### getTrendlineType {#getTrendlineType}

| Name | Description |
| --- | --- |
| getTrendlineType () | Gets or sets type of trend line. Read/write TrendlineType. |

 **Returns:**
int


---


### setBackward {#setBackward}

| Name | Description |
| --- | --- |
| setBackward (double) | Specifies the number of categories (or units on a scatter chart) that the trend line extends before the data for the series that is being trended. On scatter and non-scatter charts, the value shall be any nonnegative value. Read/write double. |


---


### setDisplayEquation {#setDisplayEquation}

| Name | Description |
| --- | --- |
| setDisplayEquation (boolean) | Specifies that the equation for the trendline is displayed on the chart (in the same label as the Rsquaredvalue). Read/write boolean. |


---


### setDisplayRSquaredValue {#setDisplayRSquaredValue}

| Name | Description |
| --- | --- |
| setDisplayRSquaredValue (boolean) | Specifies that the R-squared value of the trendline is displayed on the chart (in the same label as the equation). Read/write boolean. |


---


### setFormat {#setFormat}

| Name | Description |
| --- | --- |
| setFormat ([Format](../format)) | Represents the format of the trend line. Read/write IFormat. |


---


### setForward {#setForward}

| Name | Description |
| --- | --- |
| setForward (double) | Specifies the number of categories (or units on a scatter chart) that the trendline extends after the data for the series that is being trended. On scatter and non-scatter charts, the value shall be any non-negative value. Read/write double. |


---


### setIntercept {#setIntercept}

| Name | Description |
| --- | --- |
| setIntercept (double) | Specifies the value where the trendline shall cross the y axis. This property shall be supported only when the trendline type is exp, linear, or poly. Read/write double. |


---


### setOrder {#setOrder}

| Name | Description |
| --- | --- |
| setOrder (byte) | Specifies the order of the polynomial trend line. It is ignored for other trend line types. Value must be between 2 and 6. Read/write byte. |


---


### setPeriod {#setPeriod}

| Name | Description |
| --- | --- |
| setPeriod (byte) | Specifies the period of the trend line for a moving average trend line. It is ignored for other trend line variants. Value must be between 2 and 255. Read/write byte. |


---


### setTrendlineName {#setTrendlineName}

| Name | Description |
| --- | --- |
| setTrendlineName (String) | Gets or sets name of the trendline. Read/write String. |


---


### setTrendlineType {#setTrendlineType}

| Name | Description |
| --- | --- |
| setTrendlineType (int) | Gets or sets type of trend line. Read/write TrendlineType. |


---



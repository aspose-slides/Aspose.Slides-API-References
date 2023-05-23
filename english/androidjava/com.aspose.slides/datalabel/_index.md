---
title: DataLabel
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a series labels.
type: docs
weight: 148
url: /androidjava/com.aspose.slides/datalabel/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject
```
public class DataLabel implements IDataLabel, IDOMObject
```

Represents a series labels.
## Constructors

| Constructor | Description |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | Creates a new instance of DataLabel class. |
## Methods

| Method | Description |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Returns the parent chart. |
| [isVisible()](#isVisible--) | False means that data label is not visible (and so all Show\*-flags (ShowValue, ...) are false). |
| [hide()](#hide--) | Make data label hidden by setting all Show\*-flags (ShowValue, ...) to false state. |
| [getActualLabelText()](#getActualLabelText--) | Returns actual label text based on DataLabelFormat settings or TextFrameForOverriding.Text value. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Initialize TextFrameForOverriding with the text in paramener "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Can contain a rich formatted text. |
| [getTextFormat()](#getTextFormat--) | Returns text format. |
| [getX()](#getX--) | Returns or sets the x coordinate of a title as a fraction of the width of the chart. |
| [setX(float value)](#setX-float-) | Returns or sets the x coordinate of a title as a fraction of the width of the chart. |
| [getY()](#getY--) | Returns or sets the y coordinate of a title as a fraction of the height of the chart. |
| [setY(float value)](#setY-float-) | Returns or sets the y coordinate of a title as a fraction of the height of the chart. |
| [getWidth()](#getWidth--) | Returns or sets the width of a title as a fraction of the width of the chart. |
| [setWidth(float value)](#setWidth-float-) | Returns or sets the width of a title as a fraction of the width of the chart. |
| [getHeight()](#getHeight--) | Returns or sets the height of a title as a fraction of the height of the chart. |
| [setHeight(float value)](#setHeight-float-) | Returns or sets the height of a title as a fraction of the height of the chart. |
| [getRight()](#getRight--) | Right. |
| [getBottom()](#getBottom--) | Bottom. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Returns data label format. |
| [getValueFromCell()](#getValueFromCell--) | Gets or sets workbook data cell. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Gets or sets workbook data cell. |
| [getActualX()](#getActualX--) | Specifies actual x location (left) of the chart element relative to the left top corner of the chart. |
| [getActualY()](#getActualY--) | Specifies actual top of the chart element relative to the left top corner of the chart. |
| [getActualWidth()](#getActualWidth--) | Specifies actual width of the chart element. |
| [getActualHeight()](#getActualHeight--) | Specifies actual height of the chart element. |
| [getSlide()](#getSlide--) | Returns the parent slide of a FillFormat. |
| [getPresentation()](#getPresentation--) | Returns the parent presentation of a FillFormat. |
### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```


Creates a new instance of DataLabel class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Parent ChartDataPoint. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```


Returns the parent chart. Read-only [IChart](../../com.aspose.slides/ichart).

**Returns:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


False means that data label is not visible (and so all Show\*-flags (ShowValue, ...) are false). Read-only  boolean .

--------------------

If data label is visible you can make it hidden with Hide() method. But if data label is not visible (IsVisible is false) you can make data label visible with setting Show\*-flags (ShowValue, ...) to true state.

**Returns:**
boolean
### hide() {#hide--}
```
public final void hide()
```


Make data label hidden by setting all Show\*-flags (ShowValue, ...) to false state. IsVisible will be false after this.

--------------------

If data label is not visible (IsVisible is false) you can make data label visible with setting Show\*-flags (ShowValue, ...) to true state.

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```


Returns actual label text based on DataLabelFormat settings or TextFrameForOverriding.Text value.

**Returns:**
java.lang.String - The java.lang.String object.
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```


Initialize TextFrameForOverriding with the text in paramener "text". If TextFrameForOverriding is already initialized then simply changes its text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text for a new TextFrameForOverriding. |

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```


Can contain a rich formatted text. If this property is not null then this formatted text value overrides auto-generated text of data label. Auto-generated text of data label means text that is managed by ShowSeriesName, ShowValue, ... properties and is formatted with the TextFormatManager.TextFormat property. Read-only [ITextFrame](../../com.aspose.slides/itextframe).

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


Returns text format. Read-only [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Returns:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getX() {#getX--}
```
public final float getX()
```


Returns or sets the x coordinate of a title as a fraction of the width of the chart. Read/write  float .

**Returns:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


Returns or sets the x coordinate of a title as a fraction of the width of the chart. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```


Returns or sets the y coordinate of a title as a fraction of the height of the chart. Read/write  float .

**Returns:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


Returns or sets the y coordinate of a title as a fraction of the height of the chart. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


Returns or sets the width of a title as a fraction of the width of the chart. Read/write  float .

**Returns:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Returns or sets the width of a title as a fraction of the width of the chart. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


Returns or sets the height of a title as a fraction of the height of the chart. Read/write  float .

**Returns:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Returns or sets the height of a title as a fraction of the height of the chart. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```


Right. Read-only  float .

**Returns:**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```


Bottom. Read-only  float .

**Returns:**
float
### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```


Returns data label format. Read-only [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Returns:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```


Gets or sets workbook data cell. Applied if IDataLabelFormat.ShowLabelValueFromCell property equals true.

**Returns:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```


Gets or sets workbook data cell. Applied if IDataLabelFormat.ShowLabelValueFromCell property equals true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```


Specifies actual x location (left) of the chart element relative to the left top corner of the chart. Call method IChart.ValidateChartLayout() before to get actual values. Read  float .

**Returns:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```


Specifies actual top of the chart element relative to the left top corner of the chart. Call method IChart.ValidateChartLayout() before to get actual values. Read  float .

**Returns:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```


Specifies actual width of the chart element. Call method IChart.ValidateChartLayout() before to get actual values. Read  float .

**Returns:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```


Specifies actual height of the chart element. Call method IChart.ValidateChartLayout() before to get actual values. Read  float .

**Returns:**
float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Returns the parent slide of a FillFormat. Read-only [BaseSlide](../../com.aspose.slides/baseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Returns the parent presentation of a FillFormat. Read-only [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)

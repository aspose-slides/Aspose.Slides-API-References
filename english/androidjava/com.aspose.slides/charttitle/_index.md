---
title: ChartTitle
second_title: Aspose.Slides for Android via Java API Reference
description: Represents chart title properties.
type: docs
weight: 101
url: /androidjava/com.aspose.slides/charttitle/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IChartTitle](../../com.aspose.slides/icharttitle), com.aspose.slides.IDOMObject
```
public class ChartTitle implements IChartTitle, IDOMObject
```

Represents chart title properties.
## Methods

| Method | Description |
| --- | --- |
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
| [getOverlay()](#getOverlay--) | Determines whether other chart elements shall be allowed to overlap title. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Determines whether other chart elements shall be allowed to overlap title. |
| [getFormat()](#getFormat--) | Returns the fill, line, effect styles of a title. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Initialize TextFrameForOverriding with the text in paramener "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Can contain a rich formatted text. |
| [getTextFormat()](#getTextFormat--) | Returns text format. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Returns the parent chart. |
| [getSlide()](#getSlide--) | Returns the parent slide of a FillFormat. |
| [getPresentation()](#getPresentation--) | Returns the parent presentation of a FillFormat. |
### getX() {#getX--}
```
public final float getX()
```


Returns or sets the x coordinate of a title as a fraction of the width of the chart. Read/write float.

**Returns:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


Returns or sets the x coordinate of a title as a fraction of the width of the chart. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```


Returns or sets the y coordinate of a title as a fraction of the height of the chart. Read/write float.

**Returns:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


Returns or sets the y coordinate of a title as a fraction of the height of the chart. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


Returns or sets the width of a title as a fraction of the width of the chart. Read/write float.

**Returns:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Returns or sets the width of a title as a fraction of the width of the chart. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


Returns or sets the height of a title as a fraction of the height of the chart. Read/write float.

**Returns:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Returns or sets the height of a title as a fraction of the height of the chart. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```


Right. Read-only float.

**Returns:**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```


Bottom. Read-only float.

**Returns:**
float
### getOverlay() {#getOverlay--}
```
public final boolean getOverlay()
```


Determines whether other chart elements shall be allowed to overlap title. Read/write boolean.

**Returns:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public final void setOverlay(boolean value)
```


Determines whether other chart elements shall be allowed to overlap title. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


Returns the fill, line, effect styles of a title. Read-only [IFormat](../../com.aspose.slides/iformat).

**Returns:**
[IFormat](../../com.aspose.slides/iformat)
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


Can contain a rich formatted text. If this property is not null then this formatted text value overrides auto-generated text. Auto-generated text is an implicit property of the data label, the display unit label of the value axis, the axis title, the chart title, the label of the trendline. Auto-generated text is formatted with the IFormattedTextContainer.TextFormat property. Read-only [ITextFrame](../../com.aspose.slides/itextframe).

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


Returns text format. Read-only [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Returns:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
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

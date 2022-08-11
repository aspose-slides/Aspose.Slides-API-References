---
title: Legend
second_title: Aspose.Slides for Java API Reference
description:  Represents charts legend properties.
type: docs
weight: 266
url: /java/com.aspose.slides/legend/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ILegend](../../com.aspose.slides/ilegend)
```
public class Legend extends DomObject<Chart> implements ILegend
```

Represents chart's legend properties.
## Methods

| Method | Description |
| --- | --- |
| [getX()](#getX--) | Returns or sets the x coordinate of a legend as a fraction of the width of the chart. |
| [setX(float value)](#setX-float-) | Returns or sets the x coordinate of a legend as a fraction of the width of the chart. |
| [getY()](#getY--) | Returns or sets the y coordinate of a legend as a fraction of the height of the chart. |
| [setY(float value)](#setY-float-) | Returns or sets the y coordinate of a legend as a fraction of the height of the chart. |
| [getWidth()](#getWidth--) | Returns or sets the width of a legend as a fraction of the width of the chart. |
| [setWidth(float value)](#setWidth-float-) | Returns or sets the width of a legend as a fraction of the width of the chart. |
| [getHeight()](#getHeight--) | Returns or sets the height of a legend as a fraction of the height of the chart. |
| [setHeight(float value)](#setHeight-float-) | Returns or sets the height of a legend as a fraction of the height of the chart. |
| [getRight()](#getRight--) | Right. |
| [getBottom()](#getBottom--) | Bottom. |
| [getOverlay()](#getOverlay--) | Determines whether other chart elements shall be allowed to overlap legend. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Determines whether other chart elements shall be allowed to overlap legend. |
| [getTextFormat()](#getTextFormat--) | Text format. |
| [getPosition()](#getPosition--) | Specifies the position of the legend on a chart. |
| [setPosition(int value)](#setPosition-int-) | Specifies the position of the legend on a chart. |
| [getFormat()](#getFormat--) | Returns the format of a legend. |
| [getChart()](#getChart--) | Returns the chart. |
| [getEntries()](#getEntries--) | Gets legend entries. |
| [getSlide()](#getSlide--) | Returns the parent slide of a FillFormat. |
| [getPresentation()](#getPresentation--) | Returns the parent presentation of a FillFormat. |
### getX() {#getX--}
```
public final float getX()
```


Returns or sets the x coordinate of a legend as a fraction of the width of the chart. Read/write float.

**Returns:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


Returns or sets the x coordinate of a legend as a fraction of the width of the chart. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```


Returns or sets the y coordinate of a legend as a fraction of the height of the chart. Read/write float.

**Returns:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


Returns or sets the y coordinate of a legend as a fraction of the height of the chart. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


Returns or sets the width of a legend as a fraction of the width of the chart. Read/write float.

**Returns:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Returns or sets the width of a legend as a fraction of the width of the chart. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


Returns or sets the height of a legend as a fraction of the height of the chart. Read/write float.

**Returns:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Returns or sets the height of a legend as a fraction of the height of the chart. Read/write float.

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


Determines whether other chart elements shall be allowed to overlap legend. Read/write boolean.

**Returns:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public final void setOverlay(boolean value)
```


Determines whether other chart elements shall be allowed to overlap legend. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


Text format. Read-only [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Returns:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```


Specifies the position of the legend on a chart. Non-NaN values of X, Y, Width, Heigt properties override effect of this property. Read/write [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Returns:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


Specifies the position of the legend on a chart. Non-NaN values of X, Y, Width, Heigt properties override effect of this property. Read/write [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


Returns the format of a legend. Read-only [IFormat](../../com.aspose.slides/iformat).

**Returns:**
[IFormat](../../com.aspose.slides/iformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```


Returns the chart. Read-only [IChart](../../com.aspose.slides/ichart).

**Returns:**
[IChart](../../com.aspose.slides/ichart)
### getEntries() {#getEntries--}
```
public final ILegendEntryCollection getEntries()
```


Gets legend entries. Read-only [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection).

**Returns:**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)
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

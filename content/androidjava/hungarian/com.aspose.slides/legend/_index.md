---
title: Legend
second_title: Aspose.Slides for Android Java API-referencia
description: A diagramok jelmagyarázatának tulajdonságait reprezentálja.
type: docs
url: /hu/com.aspose.slides/legend/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ILegend](../../com.aspose.slides/ilegend)
```
public class Legend extends DomObject<Chart> implements ILegend
```

Represents chart's legend properties.
## Módszerek

| Módszer | Leírás |
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
| [getActualX()](#getActualX--) | Specifies actual x location (left) of the chart element relative to the left top corner of the chart. |
| [getActualY()](#getActualY--) | Specifies actual top of the chart element relative to the left top corner of the chart. |
| [getActualWidth()](#getActualWidth--) | Specifies actual width of the chart element. |
| [getActualHeight()](#getActualHeight--) | Specifies actual height of the chart element. |
| [getSlide()](#getSlide--) | Returns the parent slide of a FillFormat. |
| [getPresentation()](#getPresentation--) | Returns the parent presentation of a FillFormat. |
### getX() {#getX--}
```
public final float getX()
```


Returns or sets the x coordinate of a legend as a fraction of the width of the chart. Read/write float.

**Visszatérési érték:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


Returns or sets the x coordinate of a legend as a fraction of the width of the chart. Read/write float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```


Returns or sets the y coordinate of a legend as a fraction of the height of the chart. Read/write float.

**Visszatérési érték:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


Returns or sets the y coordinate of a legend as a fraction of the height of the chart. Read/write float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


Returns or sets the width of a legend as a fraction of the width of the chart. Read/write float.

**Visszatérési érték:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Returns or sets the width of a legend as a fraction of the width of the chart. Read/write float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


Returns or sets the height of a legend as a fraction of the height of the chart. Read/write float.

**Visszatérési érték:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Returns or sets the height of a legend as a fraction of the height of the chart. Read/write float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```


Right. Read-only float.

**Visszatérési érték:**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```


Bottom. Read-only float.

**Visszatérési érték:**
float
### getOverlay() {#getOverlay--}
```
public final boolean getOverlay()
```


Determines whether other chart elements shall be allowed to overlap legend. Read/write boolean.

**Visszatérési érték:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public final void setOverlay(boolean value)
```


Determines whether other chart elements shall be allowed to overlap legend. Read/write boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


Text format. Read-only [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Visszatérési érték:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```


Specifies the position of the legend on a chart. Non-NaN values of X, Y, Width, Height properties override effect of this property. Read/write [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Visszatérési érték:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


Specifies the position of the legend on a chart. Non-NaN values of X, Y, Width, Height properties override effect of this property. Read/write [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


Returns the format of a legend. Read-only [IFormat](../../com.aspose.slides/iformat).

**Visszatérési érték:**
[IFormat](../../com.aspose.slides/iformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```


Returns the chart. Read-only [IChart](../../com.aspose.slides/ichart).

**Visszatérési érték:**
[IChart](../../com.aspose.slides/ichart)
### getEntries() {#getEntries--}
```
public final ILegendEntryCollection getEntries()
```


Gets legend entries. Read-only [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection).

**Visszatérési érték:**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)
### getActualX() {#getActualX--}
```
public final float getActualX()
```


Specifies actual x location (left) of the chart element relative to the left top corner of the chart. Call method IChart.validateChartLayout() before to get actual values. Read float.

**Visszatérési érték:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```


Specifies actual top of the chart element relative to the left top corner of the chart. Call method IChart.validateChartLayout() before to get actual values. Read float.

**Visszatérési érték:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```


Specifies actual width of the chart element. Call method IChart.validateChartLayout() before to get actual values. Read float.

**Visszatérési érték:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```


Specifies actual height of the chart element. Call method IChart.validateChartLayout() before to get actual values. Read float.

**Visszatérési érték:**
float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Returns the parent slide of a FillFormat. Read-only [BaseSlide](../../com.aspose.slides/baseslide).

**Visszatérési érték:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Returns the parent presentation of a FillFormat. Read-only [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatérési érték:**
[IPresentation](../../com.aspose.slides/ipresentation)
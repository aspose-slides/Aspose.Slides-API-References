---
title: ILegend
second_title: Aspose.Slides for Java API Reference
description: Represents charts legend properties.
type: docs
weight: 851
url: /java/com.aspose.slides/ilegend/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface ILegend extends ILayoutable, IFormattedTextContainer
```

Represents chart's legend properties.
## Methods

| Method | Description |
| --- | --- |
| [getOverlay()](#getOverlay--) | Determines whether other chart elements shall be allowed to overlap legend. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Determines whether other chart elements shall be allowed to overlap legend. |
| [getPosition()](#getPosition--) | Specifies the position of the legend on a chart. |
| [setPosition(int value)](#setPosition-int-) | Specifies the position of the legend on a chart. |
| [getFormat()](#getFormat--) | Returns the format of a legend. |
| [getEntries()](#getEntries--) | Gets legend entries. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```


Determines whether other chart elements shall be allowed to overlap legend. Read/write boolean.

**Returns:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```


Determines whether other chart elements shall be allowed to overlap legend. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


Specifies the position of the legend on a chart. Non-NaN values of X, Y, Width, Heigt properties override effect of this property. Read/write [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Returns:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


Specifies the position of the legend on a chart. Non-NaN values of X, Y, Width, Heigt properties override effect of this property. Read/write [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Returns the format of a legend. Read-only [IFormat](../../com.aspose.slides/iformat).

**Returns:**
[IFormat](../../com.aspose.slides/iformat)
### getEntries() {#getEntries--}
```
public abstract ILegendEntryCollection getEntries()
```


Gets legend entries. Read-only [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection).

**Returns:**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)

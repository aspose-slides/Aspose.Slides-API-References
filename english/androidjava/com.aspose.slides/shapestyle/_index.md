---
title: ShapeStyle
second_title: Aspose.Slides for Android via Java API Reference
description: Represent shapes style reference.
type: docs
weight: 495
url: /androidjava/com.aspose.slides/shapestyle/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IShapeStyle](../../com.aspose.slides/ishapestyle)
```
public class ShapeStyle extends DomObject<Shape> implements IShapeStyle
```

Represent shape's style reference.
## Methods

| Method | Description |
| --- | --- |
| [getLineColor()](#getLineColor--) | Returns a shape's outline color. |
| [getLineStyleIndex()](#getLineStyleIndex--) | Returns or sets line's column index in a style matrix. |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | Returns or sets line's column index in a style matrix. |
| [getFillColor()](#getFillColor--) | Returns a shape's fill color. |
| [getFillStyleIndex()](#getFillStyleIndex--) | Returns or sets shape's fill column index in style matrices. |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | Returns or sets shape's fill column index in style matrices. |
| [getEffectColor()](#getEffectColor--) | Returns a shape's effect color. |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | Returns or sets shape's effect column index in a style matrix. |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | Returns or sets shape's effect column index in a style matrix. |
| [getFontColor()](#getFontColor--) | Returns a shape's font color. |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | Returns or sets shape's font index in a font collection. |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | Returns or sets shape's font index in a font collection. |
### getLineColor() {#getLineColor--}
```
public final IColorFormat getLineColor()
```


Returns a shape's outline color. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public final int getLineStyleIndex()
```


Returns or sets line's column index in a style matrix. Read/write int.

**Returns:**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public final void setLineStyleIndex(int value)
```


Returns or sets line's column index in a style matrix. Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFillColor() {#getFillColor--}
```
public final IColorFormat getFillColor()
```


Returns a shape's fill color. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public final short getFillStyleIndex()
```


Returns or sets shape's fill column index in style matrices. 0 means no fill, positive value - index in theme's fill styles, negative value - index in theme's background styles. Read/write short.

**Returns:**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public final void setFillStyleIndex(short value)
```


Returns or sets shape's fill column index in style matrices. 0 means no fill, positive value - index in theme's fill styles, negative value - index in theme's background styles. Read/write short.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getEffectColor() {#getEffectColor--}
```
public final IColorFormat getEffectColor()
```


Returns a shape's effect color. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public final long getEffectStyleIndex()
```


Returns or sets shape's effect column index in a style matrix. Read/write long.

**Returns:**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public final void setEffectStyleIndex(long value)
```


Returns or sets shape's effect column index in a style matrix. Read/write long.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getFontColor() {#getFontColor--}
```
public final IColorFormat getFontColor()
```


Returns a shape's font color. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public final byte getFontCollectionIndex()
```


Returns or sets shape's font index in a font collection. Read/write [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Returns:**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public final void setFontCollectionIndex(byte value)
```


Returns or sets shape's font index in a font collection. Read/write [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |


---
title: IShapeStyle
second_title: Aspose.Slides for Java API Reference
description: Represent shapes style reference.
type: docs
weight: 1023
url: /com.aspose.slides/ishapestyle/
---```
public interface IShapeStyle
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
public abstract IColorFormat getLineColor()
```


Returns a shape's outline color. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public abstract int getLineStyleIndex()
```


Returns or sets line's column index in a style matrix. Read/write int.

**Returns:**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public abstract void setLineStyleIndex(int value)
```


Returns or sets line's column index in a style matrix. Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFillColor() {#getFillColor--}
```
public abstract IColorFormat getFillColor()
```


Returns a shape's fill color. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public abstract short getFillStyleIndex()
```


Returns or sets shape's fill column index in style matrices. 0 means no fill, positive value - index in theme's fill styles, negative value - index in theme's background styles. Read/write short.

**Returns:**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public abstract void setFillStyleIndex(short value)
```


Returns or sets shape's fill column index in style matrices. 0 means no fill, positive value - index in theme's fill styles, negative value - index in theme's background styles. Read/write short.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getEffectColor() {#getEffectColor--}
```
public abstract IColorFormat getEffectColor()
```


Returns a shape's effect color. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public abstract long getEffectStyleIndex()
```


Returns or sets shape's effect column index in a style matrix. Read/write long.

**Returns:**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public abstract void setEffectStyleIndex(long value)
```


Returns or sets shape's effect column index in a style matrix. Read/write long.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getFontColor() {#getFontColor--}
```
public abstract IColorFormat getFontColor()
```


Returns a shape's font color. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public abstract byte getFontCollectionIndex()
```


Returns or sets shape's font index in a font collection. Read/write [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Returns:**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public abstract void setFontCollectionIndex(byte value)
```


Returns or sets shape's font index in a font collection. Read/write [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |


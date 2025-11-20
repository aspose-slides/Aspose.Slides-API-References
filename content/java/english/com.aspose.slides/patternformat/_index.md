---
title: PatternFormat
second_title: Aspose.Slides for Java API Reference
description: Represents a pattern to fill a shape.
type: docs
url: /com.aspose.slides/patternformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IPatternFormat](../../com.aspose.slides/ipatternformat)
```
public final class PatternFormat extends PVIObject implements IPatternFormat
```

Represents a pattern to fill a shape.
## Methods

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPatternStyle()](#getPatternStyle--) | Returns or sets the pattern style. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Returns or sets the pattern style. |
| [getForeColor()](#getForeColor--) | Returns the foreground pattern color. |
| [getBackColor()](#getBackColor--) | Returns the background pattern color. |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | Creates a tile image for the pattern fill with a specified colors. |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | Creates a tile image for the pattern fill. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Read-only long.

**Returns:**
long
### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```


Returns or sets the pattern style. Read/write [PatternStyle](../../com.aspose.slides/patternstyle).

**Returns:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```


Returns or sets the pattern style. Read/write [PatternStyle](../../com.aspose.slides/patternstyle).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```


Returns the foreground pattern color. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```


Returns the background pattern color. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public final IImage getTile(Color background, Color foreground)
```


Creates a tile image for the pattern fill with a specified colors.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| background | java.awt.Color | The background java.awt.Color for the pattern. |
| foreground | java.awt.Color | The foreground java.awt.Color for the pattern. |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage).
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public final IImage getTile(Color styleColor)
```


Creates a tile image for the pattern fill.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| styleColor | java.awt.Color | The default java.awt.Color |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage).

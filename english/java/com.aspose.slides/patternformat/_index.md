---
title: PatternFormat
second_title: Aspose.Slides for Java API Reference
description: Represents a pattern to fill a shape.
type: docs
weight: 407
url: /java/com.aspose.slides/patternformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IPatternFormat](../../com.aspose.slides/ipatternformat)
```
public class PatternFormat extends PVIObject implements IPatternFormat
```

Represents a pattern to fill a shape.
## Methods

| Method | Description |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Returns or sets the pattern style. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Returns or sets the pattern style. |
| [getForeColor()](#getForeColor--) | Returns the foreground pattern color. |
| [getBackColor()](#getBackColor--) | Returns the background pattern color. |
| [getTileImage(Color background, Color foreground)](#getTileImage-java.awt.Color-java.awt.Color-) | Creates a tile image for the pattern fill with a specified colors. |
| [getTileImage(Color styleColor)](#getTileImage-java.awt.Color-) | Creates a tile image for the pattern fill. |
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
### getTileImage(Color background, Color foreground) {#getTileImage-java.awt.Color-java.awt.Color-}
```
public final BufferedImage getTileImage(Color background, Color foreground)
```


Creates a tile image for the pattern fill with a specified colors.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| background | java.awt.Color | The background java.awt.Color for the pattern. |
| foreground | java.awt.Color | The foreground java.awt.Color for the pattern. |

**Returns:**
java.awt.image.BufferedImage - Tile java.awt.image.BufferedImage.
### getTileImage(Color styleColor) {#getTileImage-java.awt.Color-}
```
public final BufferedImage getTileImage(Color styleColor)
```


Creates a tile image for the pattern fill.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| styleColor | java.awt.Color | The default java.awt.Color, defined in ShapeEx's StyleEx object. Fill's colors can depend on this. |

**Returns:**
java.awt.image.BufferedImage - Tile java.awt.image.BufferedImage.

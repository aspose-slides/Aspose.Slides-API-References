---
title: IPatternFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a pattern to fill a shape.
type: docs
url: /com.aspose.slides/ipatternformat/
---```
public interface IPatternFormat
```

Represents a pattern to fill a shape.
## Methods

| Method | Description |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Returns or sets the pattern style. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Returns or sets the pattern style. |
| [getForeColor()](#getForeColor--) | Returns the foreground pattern color. |
| [getBackColor()](#getBackColor--) | Returns the background pattern color. |
| [getTileImage(Integer background, Integer foreground)](#getTileImage-java.lang.Integer-java.lang.Integer-) | Creates a tile image for the pattern fill with a specified colors. |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | Creates a tile image for the pattern fill with a specified colors. |
| [getTileImage(Integer styleColor)](#getTileImage-java.lang.Integer-) | Creates a tile image for the pattern fill. |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | Creates a tile image for the pattern fill. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


Returns or sets the pattern style. Read/write [PatternStyle](../../com.aspose.slides/patternstyle).

**Returns:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```


Returns or sets the pattern style. Read/write [PatternStyle](../../com.aspose.slides/patternstyle).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```


Returns the foreground pattern color. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```


Returns the background pattern color. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTileImage(Integer background, Integer foreground) {#getTileImage-java.lang.Integer-java.lang.Integer-}
```
public abstract Bitmap getTileImage(Integer background, Integer foreground)
```


Creates a tile image for the pattern fill with a specified colors.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| background | java.lang.Integer | The background java.lang.Integer for the pattern. |
| foreground | java.lang.Integer | The foreground java.lang.Integer for the pattern. |

**Returns:**
android.graphics.Bitmap - Tile android.graphics.Bitmap.
### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTile(Integer background, Integer foreground)
```


Creates a tile image for the pattern fill with a specified colors.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| background | java.lang.Integer | The background java.lang.Integer for the pattern. |
| foreground | java.lang.Integer | The foreground java.lang.Integer for the pattern. |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Tile android.graphics.Bitmap.
### getTileImage(Integer styleColor) {#getTileImage-java.lang.Integer-}
```
public abstract Bitmap getTileImage(Integer styleColor)
```


Creates a tile image for the pattern fill.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| styleColor | java.lang.Integer | The default java.lang.Integer, defined in ShapeEx's StyleEx object. Fill's colors can depend on this. |

**Returns:**
android.graphics.Bitmap - Tile android.graphics.Bitmap.
### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public abstract IImage getTile(Integer styleColor)
```


Creates a tile image for the pattern fill.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| styleColor | java.lang.Integer | The default java.lang.Integer, defined in ShapeEx's StyleEx object. Fill's colors can depend on this. |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Tile android.graphics.Bitmap.

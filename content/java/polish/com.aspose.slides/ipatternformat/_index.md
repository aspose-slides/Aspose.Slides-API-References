---
title: IPatternFormat
second_title: Aspose.Slides for Java API Reference
description: Represents a pattern to fill a shape.
type: docs
url: /pl/com.aspose.slides/ipatternformat/
---```
public interface IPatternFormat
```

Reprezentuje wzór wypełniający kształt.
## Metody

| Method | Description |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Returns or sets the pattern style. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Returns or sets the pattern style. |
| [getForeColor()](#getForeColor--) | Returns the foreground pattern color. |
| [getBackColor()](#getBackColor--) | Returns the background pattern color. |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | Creates a tile image for the pattern fill with a specified colors. |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | Creates a tile image for the pattern fill. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

Zwraca lub ustawia styl wzoru. Read/write [PatternStyle](../../com.aspose.slides/patternstyle).

**Returns:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```

Zwraca lub ustawia styl wzoru. Read/write [PatternStyle](../../com.aspose.slides/patternstyle).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```

Zwraca kolor pierwszoplanowy wzoru. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```

Zwraca kolor tła wzoru. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTile(Color background, Color foreground)
```

Tworzy obraz kafelka dla wypełnienia wzorem z określonymi kolorami.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| background | java.awt.Color | The background java.awt.Color for the pattern. |
| foreground | java.awt.Color | The foreground java.awt.Color for the pattern. |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Tile java.awt.image.BufferedImage.
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public abstract IImage getTile(Color styleColor)
```

Tworzy obraz kafelka dla wypełnienia wzorem.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| styleColor | java.awt.Color | The default java.awt.Color, defined in ShapeEx's StyleEx object. Fill's colors can depend on this. |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Tile java.awt.image.BufferedImage.
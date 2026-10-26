---
title: IPatternFormat
second_title: Aspose.Slides for Java API Reference
description: Represents a pattern to fill a shape.
type: docs
url: /hu/com.aspose.slides/ipatternformat/
---```
public interface IPatternFormat
```

Egy mintát képvisel egy alakzat kitöltéséhez.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Visszaadja vagy beállítja a mintastílust. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Visszaadja vagy beállítja a mintastílust. |
| [getForeColor()](#getForeColor--) | Visszaadja az előtér mintaszínét. |
| [getBackColor()](#getBackColor--) | Visszaadja a háttér mintaszínét. |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | Létrehoz egy csempe képet a minta kitöltéséhez megadott színekkel. |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | Létrehoz egy csempe képet a minta kitöltéséhez. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

Visszaadja vagy beállítja a mintastílust. Olvasás/írás [PatternStyle](../../com.aspose.slides/patternstyle).

**Visszatér:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```

Visszaadja vagy beállítja a mintastílust. Olvasás/írás [PatternStyle](../../com.aspose.slides/patternstyle).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |
### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```

Visszaadja az előtér mintaszínét. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```

Visszaadja a háttér mintaszínét. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTile(Color background, Color foreground)
```

Létrehoz egy csempe képet a minta kitöltéséhez megadott színekkel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| background | java.awt.Color | A háttér java.awt.Color a mintához. |
| foreground | java.awt.Color | Az előtér java.awt.Color a mintához. |

**Visszatér:**
[IImage](../../com.aspose.slides/iimage) - Tile java.awt.image.BufferedImage.
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public abstract IImage getTile(Color styleColor)
```

Létrehoz egy csempe képet a minta kitöltéséhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| styleColor | java.awt.Color | Az alapértelmezett java.awt.Color, a ShapeEx StyleEx objektumban definiálva. A kitöltés színei ettől függhetnek. |

**Visszatér:**
[IImage](../../com.aspose.slides/iimage) - Tile java.awt.image.BufferedImage.
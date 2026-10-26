---
title: IPatternFormat
second_title: Aspose.Slides for Android via Java API Reference
description: A forma kitöltéséhez használt mintát reprezentálja.
type: docs
url: /hu/com.aspose.slides/ipatternformat/
---```
public interface IPatternFormat
```

A forma kitöltéséhez használt mintát reprezentálja.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Returns or sets the pattern style. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Returns or sets the pattern style. |
| [getForeColor()](#getForeColor--) | Returns the foreground pattern color. |
| [getBackColor()](#getBackColor--) | Returns the background pattern color. |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | Creates a tile image for the pattern fill with a specified colors. |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | Creates a tile image for the pattern fill. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

Visszaadja vagy beállítja a minta stílusát. Olvasás/írás [PatternStyle](../../com.aspose.slides/patternstyle).

**Visszatér:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```

Visszaadja vagy beállítja a minta stílusát. Olvasás/írás [PatternStyle](../../com.aspose.slides/patternstyle).

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
### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTile(Integer background, Integer foreground)
```

Létrehozza a minta kitöltéséhez a csempe képét megadott színekkel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| background | java.lang.Integer | A minta háttér java.lang.Integer értéke. |
| foreground | java.lang.Integer | A minta előtér java.lang.Integer értéke. |

**Visszatér:**
[IImage](../../com.aspose.slides/iimage) - Csempe android.graphics.Bitmap.
### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public abstract IImage getTile(Integer styleColor)
```

Létrehozza a minta kitöltéséhez a csempe képét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| styleColor | java.lang.Integer | Az alapértelmezett java.lang.Integer, amely a ShapeEx StyleEx objektumában van definiálva. A kitöltés színei ettől függhetnek. |

**Visszatér:**
[IImage](../../com.aspose.slides/iimage) - Csempe android.graphics.Bitmap.
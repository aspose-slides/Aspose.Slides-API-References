---
title: PatternFormat
second_title: Aspose.Slides for Java API-referencia
description: Egy alakzat kitöltéséhez használt mintát képvisel.
type: docs
url: /hu/com.aspose.slides/patternformat/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Minden megvalósított interfész:**
[com.aspose.slides.IPatternFormat](../../com.aspose.slides/ipatternformat)
```
public final class PatternFormat extends PVIObject implements IPatternFormat
```

Egy alakzat kitöltéséhez használt mintát képvisel.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPatternStyle()](#getPatternStyle--) | Visszaadja vagy beállítja a minta stílusát. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Visszaadja vagy beállítja a minta stílusát. |
| [getForeColor()](#getForeColor--) | Visszaadja a minta előtér színét. |
| [getBackColor()](#getBackColor--) | Visszaadja a minta háttér színét. |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | Létrehoz egy csempeképet a minta kitöltéséhez megadott színekkel. |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | Létrehoz egy csempeképet a minta kitöltéséhez. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Verzió. Csak olvasható long.

**Visszatér:**
long
### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```

Visszaadja vagy beállítja a minta stílusát. Olvasás/írás [PatternStyle](../../com.aspose.slides/patternstyle).

**Visszatér:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```

Visszaadja vagy beállítja a minta stílusát. Olvasás/írás [PatternStyle](../../com.aspose.slides/patternstyle).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |
### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```

Visszaadja a minta előtér színét. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```

Visszaadja a minta háttér színét. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public final IImage getTile(Color background, Color foreground)
```

Létrehoz egy csempeképet a minta kitöltéséhez megadott színekkel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| background | java.awt.Color | A minta háttér java.awt.Color-ja. |
| foreground | java.awt.Color | A minta előtér java.awt.Color-ja. |

**Visszatér:**
[IImage](../../com.aspose.slides/iimage) - Csempe [IImage](../../com.aspose.slides/iimage).
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public final IImage getTile(Color styleColor)
```

Létrehoz egy csempeképet a minta kitöltéséhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| styleColor | java.awt.Color | Az alapértelmezett java.awt.Color |

**Visszatér:**
[IImage](../../com.aspose.slides/iimage) - Csempe [IImage](../../com.aspose.slides/iimage).
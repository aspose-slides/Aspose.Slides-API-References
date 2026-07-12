---
title: PatternFormat
second_title: Aspose.Slides for Android Java API referencia
description: Egy mintát képvisel, amely egy alakzat kitöltésére szolgál.
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

Olyan mintát képvisel, amely egy alakzatot tölti ki.

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPatternStyle()](#getPatternStyle--) | Returns or sets the pattern style. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Returns or sets the pattern style. |
| [getForeColor()](#getForeColor--) | Returns the foreground pattern color. |
| [getBackColor()](#getBackColor--) | Returns the background pattern color. |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | Creates a tile image for the pattern fill with a specified colors. |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | Creates a tile image for the pattern fill. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Verzió. Csak olvasható long.

**Visszatérési érték:**  
long

### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```

Visszatér vagy beállítja a mintastílust. Olvasás/írás [PatternStyle](../../com.aspose.slides/patternstyle).

**Visszatérési érték:**  
byte

### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```

Visszatér vagy beállítja a mintastílust. Olvasás/írás [PatternStyle](../../com.aspose.slides/patternstyle).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```

Visszakapja a mintafolt előtér színét. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatérési érték:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```

Visszakapja a minta háttér színét. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatérési érték:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public final IImage getTile(Integer background, Integer foreground)
```

Létrehozza a csempeképet a mintával kitöltéshez megadott színekkel.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| background | java.lang.Integer | A háttér java.lang.Integer a mintához. |
| foreground | java.lang.Integer | A előtér java.lang.Integer a mintához. |

**Visszatérési érték:**  
[IImage](../../com.aspose.slides/iimage) - Csempe [IImage](../../com.aspose.slides/iimage).

### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public final IImage getTile(Integer styleColor)
```

Létrehozza a csempeképet a mintával kitöltéshez.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| styleColor | java.lang.Integer | Az alapértelmezett java.lang.Integer |

**Visszatérési érték:**  
[IImage](../../com.aspose.slides/iimage) - Csempe [IImage](../../com.aspose.slides/iimage).
---
title: PatternFormat
second_title: Aspose.Slides för Java API-referens
description: Representerar ett mönster för att fylla en form.
type: docs
url: /sv/com.aspose.slides/patternformat/
---
**Arv:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IPatternFormat](../../com.aspose.slides/ipatternformat)
```
public final class PatternFormat extends PVIObject implements IPatternFormat
```

Representerar ett mönster för att fylla en form.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPatternStyle()](#getPatternStyle--) | Returnerar eller sätter mönsterstilen. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Returnerar eller sätter mönsterstilen. |
| [getForeColor()](#getForeColor--) | Returnerar förgrundens mönsterfärg. |
| [getBackColor()](#getBackColor--) | Returnerar bakgrundens mönsterfärg. |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | Skapar en tile-bild för mönsterfyllning med angivna färger. |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | Skapar en tile-bild för mönsterfyllning. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Skrivskyddad long.

**Returnerar:**
long
### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```

Returnerar eller sätter mönsterstilen. Läs/skriv [PatternStyle](../../com.aspose.slides/patternstyle).

**Returnerar:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```

Returnerar eller sätter mönsterstilen. Läs/skriv [PatternStyle](../../com.aspose.slides/patternstyle).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```

Returnerar förgrundens mönsterfärg. Skrivskyddad [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```

Returnerar bakgrundens mönsterfärg. Skrivskyddad [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public final IImage getTile(Color background, Color foreground)
```

Skapar en tile-bild för mönsterfyllning med angivna färger.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| background | java.awt.Color | Bakgrundens java.awt.Color för mönstret. |
| foreground | java.awt.Color | Förgrundens java.awt.Color för mönstret. |

**Returnerar:**
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage).
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public final IImage getTile(Color styleColor)
```

Skapar en tile-bild för mönsterfyllning.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| styleColor | java.awt.Color | Standard-java.awt.Color |

**Returnerar:**
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage).
---
title: PatternFormat
second_title: Aspose.Slides för Android via Java API-referens
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
| [getPatternStyle()](#getPatternStyle--) | Returnerar eller anger mönsterstilen. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Returnerar eller anger mönsterstilen. |
| [getForeColor()](#getForeColor--) | Returnerar förgrundens mönsterfärg. |
| [getBackColor()](#getBackColor--) | Returnerar bakgrundens mönsterfärg. |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | Skapar en tile-bild för mönsterfyllning med angivna färger. |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | Skapar en tile-bild för mönsterfyllning. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Endast läsning long.

**Returnerar:**
long
### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```


Returnerar eller anger mönsterstilen. Läs/skriv [PatternStyle](../../com.aspose.slides/patternstyle).

**Returnerar:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```


Returnerar eller anger mönsterstilen. Läs/skriv [PatternStyle](../../com.aspose.slides/patternstyle).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```


Returnerar förgrundens mönsterfärg. Endast läsning [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```


Returnerar bakgrundens mönsterfärg. Endast läsning [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public final IImage getTile(Integer background, Integer foreground)
```


Skapar en tile-bild för mönsterfyllning med angivna färger.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| background | java.lang.Integer | Den bakgrunds java.lang.Integer för mönstret. |
| foreground | java.lang.Integer | Den förgrunds java.lang.Integer för mönstret. |

**Returnerar:**
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage).
### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public final IImage getTile(Integer styleColor)
```


Skapar en tile-bild för mönsterfyllning.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| styleColor | java.lang.Integer | Den standard java.lang.Integer |

**Returnerar:**
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage).
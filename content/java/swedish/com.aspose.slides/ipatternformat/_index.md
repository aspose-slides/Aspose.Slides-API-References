---
title: IPatternFormat
second_title: Aspose.Slides for Java API Reference
description: Representerar ett mönster för att fylla en form.
type: docs
url: /sv/com.aspose.slides/ipatternformat/
---```
public interface IPatternFormat
```

Representerar ett mönster för att fylla en form.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Returnerar eller anger mönsterstilen. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Returnerar eller anger mönsterstilen. |
| [getForeColor()](#getForeColor--) | Returnerar förgrundens mönsterfärg. |
| [getBackColor()](#getBackColor--) | Returnerar bakgrundens mönsterfärg. |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | Skapar en kakelbild för mönsterfyllning med angivna färger. |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | Skapar en kakelbild för mönsterfyllning. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

Returnerar eller anger mönsterstilen. Läs/skriv [PatternStyle](../../com.aspose.slides/patternstyle).

**Returns:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```

Returnerar eller anger mönsterstilen. Läs/skriv [PatternStyle](../../com.aspose.slides/patternstyle).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```

Returnerar förgrundens mönsterfärg. Skrivskyddad [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```

Returnerar bakgrundens mönsterfärg. Skrivskyddad [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTile(Color background, Color foreground)
```

Skapar en kakelbild för mönsterfyllning med angivna färger.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| background | java.awt.Color | Bakgrunds-java.awt.Color för mönstret. |
| foreground | java.awt.Color | Förgrunds-java.awt.Color för mönstret. |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Tile java.awt.image.BufferedImage.
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public abstract IImage getTile(Color styleColor)
```

Skapar en kakelbild för mönsterfyllning.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| styleColor | java.awt.Color | Standard-java.awt.Color, definierad i ShapeEx:s StyleEx-objekt. Fyllningens färger kan bero på detta. |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Tile java.awt.image.BufferedImage.
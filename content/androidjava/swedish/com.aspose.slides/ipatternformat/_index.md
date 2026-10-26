---
title: IPatternFormat
second_title: Aspose.Slides för Android via Java API-referens
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
| [getPatternStyle()](#getPatternStyle--) | Returnerar eller sätter mönsterstilen. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Returnerar eller sätter mönsterstilen. |
| [getForeColor()](#getForeColor--) | Returnerar förgrundens mönsterfärg. |
| [getBackColor()](#getBackColor--) | Returnerar bakgrundens mönsterfärg. |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | Skapar en kakelbild för mönsterfyllning med angivna färger. |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | Skapar en kakelbild för mönsterfyllning. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

Returnerar eller sätter mönsterstilen. Läs/skriv [PatternStyle](../../com.aspose.slides/patternstyle).

**Returnerar:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```

Returnerar eller sätter mönsterstilen. Läs/skriv [PatternStyle](../../com.aspose.slides/patternstyle).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```

Returnerar förgrundens mönsterfärg. Skrivskyddad [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```

Returnerar bakgrundens mönsterfärg. Skrivskyddad [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTile(Integer background, Integer foreground)
```

Skapar en kakelbild för mönsterfyllning med angivna färger.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| background | java.lang.Integer | Bakgrundens java.lang.Integer för mönstret. |
| foreground | java.lang.Integer | Förgrundens java.lang.Integer för mönstret. |

**Returnerar:**
[IImage](../../com.aspose.slides/iimage) - Kakel android.graphics.Bitmap.
### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public abstract IImage getTile(Integer styleColor)
```

Skapar en kakelbild för mönsterfyllning.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| styleColor | java.lang.Integer | Den standard java.lang.Integer som definieras i ShapeEx:s StyleEx-objekt. Fyllningens färger kan bero på detta. |

**Returnerar:**
[IImage](../../com.aspose.slides/iimage) - Kakel android.graphics.Bitmap.
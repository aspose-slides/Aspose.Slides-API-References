---
title: PatternFormat
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje vzor pro výplň tvaru.
type: docs
url: /cs/com.aspose.slides/patternformat/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IPatternFormat](../../com.aspose.slides/ipatternformat)
```
public final class PatternFormat extends PVIObject implements IPatternFormat
```

Reprezentuje vzor pro výplň tvaru.
## Metody

| Metoda | Popis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPatternStyle()](#getPatternStyle--) | Vrací nebo nastavuje styl vzoru. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Vrací nebo nastavuje styl vzoru. |
| [getForeColor()](#getForeColor--) | Vrací barvu popředí vzoru. |
| [getBackColor()](#getBackColor--) | Vrací barvu pozadí vzoru. |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | Vytváří dlaždicový obrázek pro výplň vzorem se specifikovanými barvami. |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | Vytváří dlaždicový obrázek pro výplň vzorem. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Verze. Pouze pro čtení long.

**Vrací:**
long
### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```

Vrací nebo nastavuje styl vzoru. Čtení/Zápis [PatternStyle](../../com.aspose.slides/patternstyle).

**Vrací:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```

Vrací nebo nastavuje styl vzoru. Čtení/Zápis [PatternStyle](../../com.aspose.slides/patternstyle).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```

Vrací barvu popředí vzoru. Pouze pro čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```

Vrací barvu pozadí vzoru. Pouze pro čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public final IImage getTile(Integer background, Integer foreground)
```

Vytváří dlaždicový obrázek pro výplň vzorem se specifikovanými barvami.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| background | java.lang.Integer | Pozadí java.lang.Integer pro vzor. |
| foreground | java.lang.Integer | Popředí java.lang.Integer pro vzor. |

**Vrací:**
[IImage](../../com.aspose.slides/iimage) - Dlaždice [IImage](../../com.aspose.slides/iimage).
### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public final IImage getTile(Integer styleColor)
```

Vytváří dlaždicový obrázek pro výplň vzorem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| styleColor | java.lang.Integer | Výchozí java.lang.Integer |

**Vrací:**
[IImage](../../com.aspose.slides/iimage) - Dlaždice [IImage](../../com.aspose.slides/iimage).
---
title: PatternFormat
second_title: Aspose.Slides pro Java – reference API
description: Reprezentuje vzor pro výplň tvaru.
type: docs
url: /cs/com.aspose.slides/patternformat/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Všechny implementované rozhraní:**
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
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | Vytvoří obrázek dlaždice pro výplň vzoru se specifikovanými barvami. |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | Vytvoří obrázek dlaždice pro výplň vzoru. |
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

Vrací nebo nastavuje styl vzoru. Čtení/zápis [PatternStyle](../../com.aspose.slides/patternstyle).

**Vrací:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```

Vrací nebo nastavuje styl vzoru. Čtení/zápis [PatternStyle](../../com.aspose.slides/patternstyle).

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
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public final IImage getTile(Color background, Color foreground)
```

Vytvoří obrázek dlaždice pro výplň vzoru se specifikovanými barvami.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| background | java.awt.Color | Barva pozadí java.awt.Color pro vzor. |
| foreground | java.awt.Color | Barva popředí java.awt.Color pro vzor. |

**Vrací:**
[IImage](../../com.aspose.slides/iimage) - Dlaždice [IImage](../../com.aspose.slides/iimage).
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public final IImage getTile(Color styleColor)
```

Vytvoří obrázek dlaždice pro výplň vzoru.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| styleColor | java.awt.Color | Výchozí java.awt.Color |

**Vrací:**
[IImage](../../com.aspose.slides/iimage) - Dlaždice [IImage](../../com.aspose.slides/iimage).
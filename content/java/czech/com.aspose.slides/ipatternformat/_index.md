---
title: IPatternFormat
second_title: Aspose.Slides for Java API Reference
description: Představuje vzor pro vyplnění tvaru.
type: docs
url: /cs/com.aspose.slides/ipatternformat/
---```
public interface IPatternFormat
```

Představuje vzor pro vyplnění tvaru.
## Metody

| Metoda | Popis |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Vrací nebo nastavuje styl vzoru. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Vrací nebo nastavuje styl vzoru. |
| [getForeColor()](#getForeColor--) | Vrací barvu popředí vzoru. |
| [getBackColor()](#getBackColor--) | Vrací barvu pozadí vzoru. |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | Vytvoří obrázek dlaždice pro vyplnění vzoru se zadanými barvami. |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | Vytvoří obrázek dlaždice pro vyplnění vzoru. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

Vrací nebo nastavuje styl vzoru. Čtení/Zápis [PatternStyle](../../com.aspose.slides/patternstyle).

**Vrací:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```

Vrací nebo nastavuje styl vzoru. Čtení/Zápis [PatternStyle](../../com.aspose.slides/patternstyle).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```

Vrací barvu popředí vzoru. Pouze ke čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```

Vrací barvu pozadí vzoru. Pouze ke čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTile(Color background, Color foreground)
```

Vytvoří obrázek dlaždice pro vyplnění vzoru se zadanými barvami.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| background | java.awt.Color | Barva pozadí java.awt.Color pro vzor. |
| foreground | java.awt.Color | Barva popředí java.awt.Color pro vzor. |

**Vrací:**
[IImage](../../com.aspose.slides/iimage) - Dlaždice java.awt.image.BufferedImage.
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public abstract IImage getTile(Color styleColor)
```

Vytvoří obrázek dlaždice pro vyplnění vzoru.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| styleColor | java.awt.Color | Výchozí java.awt.Color, definovaný v objektu StyleEx třídy ShapeEx. Barvy výplně mohou záviset na tomto. |

**Vrací:**
[IImage](../../com.aspose.slides/iimage) - Dlaždice java.awt.image.BufferedImage.
---
title: IPatternFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a pattern to fill a shape.
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
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | Vytváří dlaždicový obrázek pro výplň vzoru s určenými barvami. |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | Vytváří dlaždicový obrázek pro výplň vzoru. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


Vrací nebo nastavuje styl vzoru. Čtení/zápis [PatternStyle](../../com.aspose.slides/patternstyle).

**Vrací:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```


Vrací nebo nastavuje styl vzoru. Čtení/zápis [PatternStyle](../../com.aspose.slides/patternstyle).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```


Vrací barvu popředí vzoru. Pouze pro čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```


Vrací barvu pozadí vzoru. Pouze pro čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTile(Integer background, Integer foreground)
```


Vytváří dlaždicový obrázek pro výplň vzoru s určenými barvami.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| background | java.lang.Integer | Pozadí java.lang.Integer pro vzor. |
| foreground | java.lang.Integer | Popředí java.lang.Integer pro vzor. |

**Vrací:**
[IImage](../../com.aspose.slides/iimage) - Dlaždice android.graphics.Bitmap.
### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public abstract IImage getTile(Integer styleColor)
```


Vytváří dlaždicový obrázek pro výplň vzoru.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| styleColor | java.lang.Integer | Výchozí java.lang.Integer, definovaný v objektu StyleEx třídy ShapeEx. Barvy výplně mohou záviset na tomto. |

**Vrací:**
[IImage](../../com.aspose.slides/iimage) - Dlaždice android.graphics.Bitmap.
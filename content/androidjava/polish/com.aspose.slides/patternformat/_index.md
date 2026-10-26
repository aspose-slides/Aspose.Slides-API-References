---
title: PatternFormat
second_title: Aspose.Slides dla Androida – odwołanie do Java API
description: Reprezentuje wzór do wypełniania kształtu.
type: docs
url: /pl/com.aspose.slides/patternformat/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IPatternFormat](../../com.aspose.slides/ipatternformat)
```
public final class PatternFormat extends PVIObject implements IPatternFormat
```

Reprezentuje wzór do wypełniania kształtu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPatternStyle()](#getPatternStyle--) | Zwraca lub ustawia styl wzoru. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Zwraca lub ustawia styl wzoru. |
| [getForeColor()](#getForeColor--) | Zwraca kolor pierwszoplanowy wzoru. |
| [getBackColor()](#getBackColor--) | Zwraca kolor tła wzoru. |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | Tworzy obraz kafelka dla wypełnienia wzorem z określonymi kolorami. |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | Tworzy obraz kafelka dla wypełnienia wzorem. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Wersja. Tylko do odczytu, typ long.

**Zwraca:**
long
### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```


Zwraca lub ustawia styl wzoru. Do odczytu/zapisu [PatternStyle](../../com.aspose.slides/patternstyle).

**Zwraca:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```


Zwraca lub ustawia styl wzoru. Do odczytu/zapisu [PatternStyle](../../com.aspose.slides/patternstyle).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```


Zwraca kolor pierwszoplanowy wzoru. Tylko do odczytu [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```


Zwraca kolor tła wzoru. Tylko do odczytu [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public final IImage getTile(Integer background, Integer foreground)
```


Tworzy obraz kafelka dla wypełnienia wzorem z określonymi kolorami.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| background | java.lang.Integer | The background java.lang.Integer for the pattern. |
| foreground | java.lang.Integer | The foreground java.lang.Integer for the pattern. |

**Zwraca:**
[IImage](../../com.aspose.slides/iimage) - Kafelek [IImage](../../com.aspose.slides/iimage).
### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public final IImage getTile(Integer styleColor)
```


Tworzy obraz kafelka dla wypełnienia wzorem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| styleColor | java.lang.Integer | The default java.lang.Integer |

**Zwraca:**
[IImage](../../com.aspose.slides/iimage) - Kafelek [IImage](../../com.aspose.slides/iimage).
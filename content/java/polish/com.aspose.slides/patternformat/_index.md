---
title: PatternFormat
second_title: Aspose.Slides dla Java – odniesienie API
description: Reprezentuje wzorzec do wypełniania kształtu.
type: docs
url: /pl/com.aspose.slides/patternformat/
---
**Dziedziczenie:** [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Wszystkie zaimplementowane interfejsy:**  
[com.aspose.slides.IPatternFormat](../../com.aspose.slides/ipatternformat)  
```
public final class PatternFormat extends PVIObject implements IPatternFormat
```

Reprezentuje wzorzec do wypełniania kształtu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPatternStyle()](#getPatternStyle--) | Zwraca lub ustawia styl wzorca. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Zwraca lub ustawia styl wzorca. |
| [getForeColor()](#getForeColor--) | Zwraca kolor pierwszoplanowego wzorca. |
| [getBackColor()](#getBackColor--) | Zwraca kolor tła wzorca. |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | Tworzy obraz kafelka dla wypełnienia wzorcem z określonymi kolorami. |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | Tworzy obraz kafelka dla wypełnienia wzorcem. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Wersja. Tylko do odczytu long.

**Zwraca:**  
long
### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```

Zwraca lub ustawia styl wzorca. Odczyt/zapis [PatternStyle](../../com.aspose.slides/patternstyle).

**Zwraca:**  
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```

Zwraca lub ustawia styl wzorca. Odczyt/zapis [PatternStyle](../../com.aspose.slides/patternstyle).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |
### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```

Zwraca kolor pierwszoplanowego wzorca. Tylko do odczytu [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```

Zwraca kolor tła wzorca. Tylko do odczytu [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public final IImage getTile(Color background, Color foreground)
```

Tworzy obraz kafelka dla wypełnienia wzorcem z określonymi kolorami.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| background | java.awt.Color | Kolor tła java.awt.Color dla wzorca. |
| foreground | java.awt.Color | Kolor pierwszoplanowy java.awt.Color dla wzorca. |

**Zwraca:**  
[IImage](../../com.aspose.slides/iimage) - Kafelek [IImage](../../com.aspose.slides/iimage).
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public final IImage getTile(Color styleColor)
```

Tworzy obraz kafelka dla wypełnienia wzorcem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| styleColor | java.awt.Color | Domyślny java.awt.Color |

**Zwraca:**  
[IImage](../../com.aspose.slides/iimage) - Kafelek [IImage](../../com.aspose.slides/iimage).
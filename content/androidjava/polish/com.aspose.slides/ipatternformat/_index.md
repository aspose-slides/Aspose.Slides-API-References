---
title: IPatternFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a pattern to fill a shape.
type: docs
url: /pl/com.aspose.slides/ipatternformat/
---```
public interface IPatternFormat
```

Reprezentuje wzór służący do wypełniania kształtu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Zwraca lub ustawia styl wzoru. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Zwraca lub ustawia styl wzoru. |
| [getForeColor()](#getForeColor--) | Zwraca kolor pierwszoplanowy wzoru. |
| [getBackColor()](#getBackColor--) | Zwraca kolor tła wzoru. |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | Tworzy obraz kafelka do wypełnienia wzorem z określonymi kolorami. |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | Tworzy obraz kafelka do wypełnienia wzorem. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


Zwraca lub ustawia styl wzoru. Odczyt/zapis [PatternStyle](../../com.aspose.slides/patternstyle).

**Zwraca:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```


Zwraca lub ustawia styl wzoru. Odczyt/zapis [PatternStyle](../../com.aspose.slides/patternstyle).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```


Zwraca kolor pierwszoplanowy wzoru. Tylko do odczytu [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```


Zwraca kolor tła wzoru. Tylko do odczytu [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTile(Integer background, Integer foreground)
```


Tworzy obraz kafelka do wypełnienia wzorem z określonymi kolorami.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| background | java.lang.Integer | Tło java.lang.Integer dla wzoru. |
| foreground | java.lang.Integer | Pierwszoplanowy java.lang.Integer dla wzoru. |

**Zwraca:**
[IImage](../../com.aspose.slides/iimage) - Kafelek android.graphics.Bitmap.
### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public abstract IImage getTile(Integer styleColor)
```


Tworzy obraz kafelka do wypełnienia wzorem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| styleColor | java.lang.Integer | Domyślny java.lang.Integer, zdefiniowany w obiekcie StyleEx klasy ShapeEx. Kolory wypełnienia mogą zależeć od tego. |

**Zwraca:**
[IImage](../../com.aspose.slides/iimage) - Kafelek android.graphics.Bitmap.
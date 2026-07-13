---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides dla Androida poprzez Java API Reference
description: Niezmienny obiekt zawierający efektywne właściwości wypełniania wzorcem.
type: docs
url: /pl/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

Niezmienny obiekt zawierający efektywne właściwości wypełniania wzorcem.

--------------------

Ten interfejs jest używany jako część [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) i [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Metody

| Metoda | Opis |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Zwraca styl wzoru. |
| [getForeColor()](#getForeColor--) | Zwraca kolor pierwszoplanowego wzoru. |
| [getBackColor()](#getBackColor--) | Zwraca kolor tła wzoru. |
| [getTileIImage(Integer background, Integer foreground)](#getTileIImage-java.lang.Integer-java.lang.Integer-) | Tworzy obraz kafla dla wypełnienia wzorem z określonymi kolorami. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


Zwraca styl wzoru. Tylko do odczytu [PatternStyle](../../com.aspose.slides/patternstyle).

**Zwraca:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Integer getForeColor()
```


Zwraca kolor pierwszoplanowego wzoru. Tylko do odczytu java.lang.Integer.

**Zwraca:**
java.lang.Integer
### getBackColor() {#getBackColor--}
```
public abstract Integer getBackColor()
```


Zwraca kolor tła wzoru. Tylko do odczytu java.lang.Integer.

**Zwraca:**
java.lang.Integer
### getTileIImage(Integer background, Integer foreground) {#getTileIImage-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTileIImage(Integer background, Integer foreground)
```


Tworzy obraz kafla dla wypełnienia wzorem z określonymi kolorami.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| background | java.lang.Integer | Wartość java.lang.Integer określająca tło wzoru. |
| foreground | java.lang.Integer | Wartość java.lang.Integer określająca pierwszy plan wzoru. |

**Zwraca:**
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage).
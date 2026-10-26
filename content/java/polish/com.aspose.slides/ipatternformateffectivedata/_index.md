---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Niezmienny obiekt zawierający skuteczne właściwości wypełniania wzorem.
type: docs
url: /pl/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

Niezmienny obiekt zawierający skuteczne właściwości wypełniania wzorem.

--------------------

Ten interfejs jest używany jako część [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) i [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Metody

| Metoda | Opis |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Zwraca styl wzoru. |
| [getForeColor()](#getForeColor--) | Zwraca kolor pierwszoplanowego wzoru. |
| [getBackColor()](#getBackColor--) | Zwraca kolor tła wzoru. |
| [getTileIImage(Color background, Color foreground)](#getTileIImage-java.awt.Color-java.awt.Color-) | Tworzy obraz kafelka dla wypełnienia wzorem z określonymi kolorami. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

Zwraca styl wzoru. Tylko do odczytu [PatternStyle](../../com.aspose.slides/patternstyle).

**Zwraca:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Color getForeColor()
```

Zwraca kolor pierwszoplanowego wzoru. Tylko do odczytu java.awt.Color.

**Zwraca:**
java.awt.Color
### getBackColor() {#getBackColor--}
```
public abstract Color getBackColor()
```

Zwraca kolor tła wzoru. Tylko do odczytu java.awt.Color.

**Zwraca:**
java.awt.Color
### getTileIImage(Color background, Color foreground) {#getTileIImage-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTileIImage(Color background, Color foreground)
```

Tworzy obraz kafelka dla wypełnienia wzorem z określonymi kolorami.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| background | java.awt.Color | Kolor tła java.awt.Color dla wzoru. |
| foreground | java.awt.Color | Kolor pierwszoplanowy java.awt.Color dla wzoru. |

**Zwraca:**
[IImage](../../com.aspose.slides/iimage) - Kafel [IImage](../../com.aspose.slides/iimage).
---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective pattern filling properties.
type: docs
url: /cs/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

Neměnný objekt, který obsahuje efektivní vlastnosti výplně vzoru.

--------------------

Toto rozhraní se používá jako součást [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) a [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Metody

| Metoda | Popis |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Vrací styl vzoru. |
| [getForeColor()](#getForeColor--) | Vrací barvu popředí vzoru. |
| [getBackColor()](#getBackColor--) | Vrací barvu pozadí vzoru. |
| [getTileIImage(Color background, Color foreground)](#getTileIImage-java.awt.Color-java.awt.Color-) | Vytváří dlaždicový obrázek pro výplň vzoru s určenými barvami. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

Vrací styl vzoru. Pouze ke čtení [PatternStyle](../../com.aspose.slides/patternstyle).

**Returns:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Color getForeColor()
```

Vrací barvu popředí vzoru. Pouze ke čtení java.awt.Color.

**Returns:**
java.awt.Color
### getBackColor() {#getBackColor--}
```
public abstract Color getBackColor()
```

Vrací barvu pozadí vzoru. Pouze ke čtení java.awt.Color.

**Returns:**
java.awt.Color
### getTileIImage(Color background, Color foreground) {#getTileIImage-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTileIImage(Color background, Color foreground)
```

Vytváří dlaždicový obrázek pro výplň vzoru s určenými barvami.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| background | java.awt.Color | Pozadí java.awt.Color pro vzor. |
| foreground | java.awt.Color | Popředí java.awt.Color pro vzor. |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage).
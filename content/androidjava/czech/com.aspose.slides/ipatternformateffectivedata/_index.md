---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Neměnný objekt, který obsahuje efektivní vlastnosti výplně vzoru.
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
| [getTileIImage(Integer background, Integer foreground)](#getTileIImage-java.lang.Integer-java.lang.Integer-) | Vytváří dlaždicový obrázek pro výplň vzoru se specifikovanými barvami. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

Vrací styl vzoru. Pouze pro čtení [PatternStyle](../../com.aspose.slides/patternstyle).

**Vrací:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Integer getForeColor()
```

Vrací barvu popředí vzoru. Pouze pro čtení java.lang.Integer.

**Vrací:**
java.lang.Integer
### getBackColor() {#getBackColor--}
```
public abstract Integer getBackColor()
```

Vrací barvu pozadí vzoru. Pouze pro čtení java.lang.Integer.

**Vrací:**
java.lang.Integer
### getTileIImage(Integer background, Integer foreground) {#getTileIImage-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTileIImage(Integer background, Integer foreground)
```

Vytváří dlaždicový obrázek pro výplň vzoru se specifikovanými barvami.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| background | java.lang.Integer | Pozadí java.lang.Integer pro vzor. |
| foreground | java.lang.Integer | Popředí java.lang.Integer pro vzor. |

**Vrací:**
[IImage](../../com.aspose.slides/iimage) - Dlaždice [IImage](../../com.aspose.slides/iimage).
---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides for Android a Java API referencián keresztül
description: Megváltoztathatatlan objektum, amely hatékony mintafelöltési tulajdonságokat tartalmaz.
type: docs
url: /hu/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

Megváltoztathatatlan objektum, amely hatékony mintafelöltési tulajdonságokat tartalmaz.

--------------------

Ez a felület a [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) és [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata) részeként használatos.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Visszaadja a minta stílusát. |
| [getForeColor()](#getForeColor--) | Visszaadja a minta előtérszínét. |
| [getBackColor()](#getBackColor--) | Visszaadja a minta háttérszínét. |
| [getTileIImage(Integer background, Integer foreground)](#getTileIImage-java.lang.Integer-java.lang.Integer-) | Létrehoz egy csempe képet a mintafelöltéshez a megadott színekkel. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

Visszaadja a minta stílusát. Csak olvasható [PatternStyle](../../com.aspose.slides/patternstyle).

**Visszaad:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Integer getForeColor()
```

Visszaadja a minta előtérszínét. Csak olvasható java.lang.Integer.

**Visszaad:**
java.lang.Integer
### getBackColor() {#getBackColor--}
```
public abstract Integer getBackColor()
```

Visszaadja a minta háttérszínét. Csak olvasható java.lang.Integer.

**Visszaad:**
java.lang.Integer
### getTileIImage(Integer background, Integer foreground) {#getTileIImage-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTileIImage(Integer background, Integer foreground)
```

Létrehoz egy csempe képet a mintafelöltéshez a megadott színekkel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| background | java.lang.Integer | A minta háttér java.lang.Integer értéke. |
| foreground | java.lang.Integer | A minta előtér java.lang.Integer értéke. |

**Visszaad:**
[IImage](../../com.aspose.slides/iimage) - csempe [IImage](../../com.aspose.slides/iimage).
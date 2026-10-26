---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Onveranderlijk object dat effectieve patroonvullingseigenschappen bevat.
type: docs
url: /nl/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

Onveranderlijk object dat effectieve patroonvullingseigenschappen bevat.

--------------------

Deze interface wordt gebruikt als onderdeel van [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) en [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Methodes

| Methode | Beschrijving |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Returns the pattern style. |
| [getForeColor()](#getForeColor--) | Returns the foreground pattern color. |
| [getBackColor()](#getBackColor--) | Returns the background pattern color. |
| [getTileIImage(Integer background, Integer foreground)](#getTileIImage-java.lang.Integer-java.lang.Integer-) | Creates a tile image for the pattern fill with a specified colors. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

Retourneert de patroonstijl. Alleen-lezen [PatternStyle](../../com.aspose.slides/patternstyle).

**Returns:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Integer getForeColor()
```

Retourneert de voorgrondpatroonkleur. Alleen-lezen java.lang.Integer.

**Returns:**
java.lang.Integer
### getBackColor() {#getBackColor--}
```
public abstract Integer getBackColor()
```

Retourneert de achtergrondpatroonkleur. Alleen-lezen java.lang.Integer.

**Returns:**
java.lang.Integer
### getTileIImage(Integer background, Integer foreground) {#getTileIImage-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTileIImage(Integer background, Integer foreground)
```

Maakt een tegelafbeelding voor de patroonvulling met opgegeven kleuren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| background | java.lang.Integer | De achtergrond java.lang.Integer voor het patroon. |
| foreground | java.lang.Integer | De voorgrond java.lang.Integer voor het patroon. |

**Retour:**
[IImage](../../com.aspose.slides/iimage) - Tegel [IImage](../../com.aspose.slides/iimage).
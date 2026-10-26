---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Onveranderlijk object dat effectieve patroonvullingseigenschappen bevat.
type: docs
url: /nl/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

Onveranderlijk object dat effectieve patroonvullingseigenschappen bevat.

--------------------

This interface is used as a part of [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) and [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Retourneert de patroonstijl. |
| [getForeColor()](#getForeColor--) | Retourneert de voorgrond patroonkleur. |
| [getBackColor()](#getBackColor--) | Retourneert de achtergrond patroonkleur. |
| [getTileIImage(Color background, Color foreground)](#getTileIImage-java.awt.Color-java.awt.Color-) | Maakt een tegelafbeelding voor de patroonvulling met opgegeven kleuren. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


Retourneert de patroonstijl. Alleen-lezen [PatternStyle](../../com.aspose.slides/patternstyle).

**Retourneert:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Color getForeColor()
```


Retourneert de voorgrond patroonkleur. Alleen-lezen java.awt.Color.

**Retourneert:**
java.awt.Color
### getBackColor() {#getBackColor--}
```
public abstract Color getBackColor()
```


Retourneert de achtergrond patroonkleur. Alleen-lezen java.awt.Color.

**Retourneert:**
java.awt.Color
### getTileIImage(Color background, Color foreground) {#getTileIImage-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTileIImage(Color background, Color foreground)
```


Maakt een tegelafbeelding voor de patroonvulling met opgegeven kleuren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| background | java.awt.Color | De achtergrond java.awt.Color voor het patroon. |
| foreground | java.awt.Color | De voorgrond java.awt.Color voor het patroon. |

**Retourneert:**
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage).
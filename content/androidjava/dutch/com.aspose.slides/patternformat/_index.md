---
title: PatternFormat
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een patroon voor om een vorm te vullen.
type: docs
url: /nl/com.aspose.slides/patternformat/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IPatternFormat](../../com.aspose.slides/ipatternformat)
```
public final class PatternFormat extends PVIObject implements IPatternFormat
```

Stelt een patroon voor om een vorm te vullen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPatternStyle()](#getPatternStyle--) | Retourneert of stelt de patroonstijl in. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Retourneert of stelt de patroonstijl in. |
| [getForeColor()](#getForeColor--) | Retourneert de voorgrondpatroonkleur. |
| [getBackColor()](#getBackColor--) | Retourneert de achtergrondpatroonkleur. |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | Creëert een tegelafbeelding voor het patroonvulling met gespecificeerde kleuren. |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | Creëert een tegelafbeelding voor het patroonvulling. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versie. Alleen-lezen long.

**Retour:**
long
### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```


Retourneert of stelt de patroonstijl in. Lezen/Schrijven [PatternStyle](../../com.aspose.slides/patternstyle).

**Retour:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```


Retourneert of stelt de patroonstijl in. Lezen/Schrijven [PatternStyle](../../com.aspose.slides/patternstyle).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```


Retourneert de voorgrondpatroonkleur. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```


Retourneert de achtergrondpatroonkleur. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public final IImage getTile(Integer background, Integer foreground)
```


Creëert een tegelafbeelding voor het patroonvulling met gespecificeerde kleuren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| background | java.lang.Integer | De achtergrond java.lang.Integer voor het patroon. |
| foreground | java.lang.Integer | De voorgrond java.lang.Integer voor het patroon. |

**Retour:**
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage).
### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public final IImage getTile(Integer styleColor)
```


Creëert een tegelafbeelding voor het patroonvulling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| styleColor | java.lang.Integer | De standaard java.lang.Integer |

**Retour:**
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage).
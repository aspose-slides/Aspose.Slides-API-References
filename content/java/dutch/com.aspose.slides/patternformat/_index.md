---
title: PatternFormat
second_title: Aspose.Slides voor Java API Referentie
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
| [getForeColor()](#getForeColor--) | Retourneert de voorgrond patroonkleur. |
| [getBackColor()](#getBackColor--) | Retourneert de achtergrond patroonkleur. |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | Maakt een tegelafbeelding voor de patroonvulling met opgegeven kleuren. |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | Maakt een tegelafbeelding voor de patroonvulling. |

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

Retourneert of stelt de patroonstijl in. Lees/schrijf [PatternStyle](../../com.aspose.slides/patternstyle).

**Retour:**  
byte

### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```

Retourneert of stelt de patroonstijl in. Lees/schrijf [PatternStyle](../../com.aspose.slides/patternstyle).

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```

Retourneert de voorgrond patroonkleur. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```

Retourneert de achtergrond patroonkleur. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public final IImage getTile(Color background, Color foreground)
```

Maakt een tegelafbeelding voor de patroonvulling met opgegeven kleuren.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| background | java.awt.Color | De achtergrond java.awt.Color voor het patroon. |
| foreground | java.awt.Color | De voorgrond java.awt.Color voor het patroon. |

**Retour:**  
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage).

### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public final IImage getTile(Color styleColor)
```

Maakt een tegelafbeelding voor de patroonvulling.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| styleColor | java.awt.Color | De standaard java.awt.Color |

**Retour:**  
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage).
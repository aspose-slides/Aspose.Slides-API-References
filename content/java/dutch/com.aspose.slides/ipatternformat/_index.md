---
title: IPatternFormat
second_title: Aspose.Slides for Java API Reference
description: Stelt een patroon voor om een vorm te vullen.
type: docs
url: /nl/com.aspose.slides/ipatternformat/
---```
public interface IPatternFormat
```

Stelt een patroon voor om een vorm te vullen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Retourneert of stelt de patroonstijl in. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Retourneert of stelt de patroonstijl in. |
| [getForeColor()](#getForeColor--) | Retourneert de voorgrond patroonkleur. |
| [getBackColor()](#getBackColor--) | Retourneert de achtergrond patroonkleur. |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | Maakt een tegelafbeelding voor de patroonvulling met opgegeven kleuren. |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | Maakt een tegelafbeelding voor de patroonvulling. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

Retourneert of stelt de patroonstijl in. Lezen/Schrijven [PatternStyle](../../com.aspose.slides/patternstyle).

**Retour:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```

Retourneert of stelt de patroonstijl in. Lezen/Schrijven [PatternStyle](../../com.aspose.slides/patternstyle).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```

Retourneert de voorgrond patroonkleur. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```

Retourneert de achtergrond patroonkleur. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTile(Color background, Color foreground)
```

Maakt een tegelafbeelding voor de patroonvulling met opgegeven kleuren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| background | java.awt.Color | De achtergrond java.awt.Color voor het patroon. |
| foreground | java.awt.Color | De voorgrond java.awt.Color voor het patroon. |

**Retour:**
[IImage](../../com.aspose.slides/iimage) - Tile java.awt.image.BufferedImage.
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public abstract IImage getTile(Color styleColor)
```

Maakt een tegelafbeelding voor de patroonvulling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| styleColor | java.awt.Color | De standaard java.awt.Color, gedefinieerd in het StyleEx-object van ShapeEx. De kleuren van de vulling kunnen hiervan afhankelijk zijn. |

**Retour:**
[IImage](../../com.aspose.slides/iimage) - Tile java.awt.image.BufferedImage.
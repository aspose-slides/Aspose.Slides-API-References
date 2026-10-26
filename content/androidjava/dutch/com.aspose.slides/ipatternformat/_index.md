---
title: IPatternFormat
second_title: Aspose.Slides for Android via Java API Reference
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
| [getPatternStyle()](#getPatternStyle--) | Geeft de patroonstijl terug of stelt deze in. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Geeft de patroonstijl terug of stelt deze in. |
| [getForeColor()](#getForeColor--) | Geeft de voorgrond patroonkleur terug. |
| [getBackColor()](#getBackColor--) | Geeft de achtergrond patroonkleur terug. |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | Maakt een tegelafbeelding voor de patroonvulling met opgegeven kleuren. |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | Maakt een tegelafbeelding voor de patroonvulling. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


Geeft de patroonstijl terug of stelt deze in. Lezen/schrijven [PatternStyle](../../com.aspose.slides/patternstyle).

**Retour:**  
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```


Geeft de patroonstijl terug of stelt deze in. Lezen/schrijven [PatternStyle](../../com.aspose.slides/patternstyle).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```


Geeft de voorgrond patroonkleur terug. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```


Geeft de achtergrond patroonkleur terug. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTile(Integer background, Integer foreground)
```


Maakt een tegelafbeelding voor de patroonvulling met opgegeven kleuren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| background | java.lang.Integer | De achtergrond java.lang.Integer voor het patroon. |
| foreground | java.lang.Integer | De voorgrond java.lang.Integer voor het patroon. |

**Retour:**  
[IImage](../../com.aspose.slides/iimage) - Tile android.graphics.Bitmap.
### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public abstract IImage getTile(Integer styleColor)
```


Maakt een tegelafbeelding voor de patroonvulling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| styleColor | java.lang.Integer | De standaard java.lang.Integer, gedefinieerd in ShapeEx's StyleEx-object. De kleuren van de vulling kunnen hiervan afhangen. |

**Retour:**  
[IImage](../../com.aspose.slides/iimage) - Tile android.graphics.Bitmap.
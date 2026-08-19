---
title: IDrawingGuide
second_title: Aspose.Slides for Java API Reference
description: Stelt een verstelbare tekenrichtlijn voor.
type: docs
url: /nl/com.aspose.slides/idrawingguide/
---```
public interface IDrawingGuide
```

Stelt een verstelbare tekenrichtlijn voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getOrientation()](#getOrientation--) | Geeft of stelt de oriëntatie van de tekenrichtlijn in. |
| [setOrientation(byte value)](#setOrientation-byte-) | Geeft of stelt de oriëntatie van de tekenrichtlijn in. |
| [getPosition()](#getPosition--) | Geeft of stelt de positie van de tekenrichtlijn in punten vanaf de boven- en linkerhoek van de dia in. |
| [setPosition(float value)](#setPosition-float-) | Geeft of stelt de positie van de tekenrichtlijn in punten vanaf de boven- en linkerhoek van de dia in. |
| [getColor()](#getColor--) | Geeft of stelt de kleur van de tekenrichtlijn in. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Geeft of stelt de kleur van de tekenrichtlijn in. |
### getOrientation() {#getOrientation--}
```
public abstract byte getOrientation()
```

Geeft of stelt de oriëntatie van de tekenrichtlijn in. Lezen/Schrijven [Orientation](../../com.aspose.slides/orientation).

**Retour:**
byte
### setOrientation(byte value) {#setOrientation-byte-}
```
public abstract void setOrientation(byte value)
```

Geeft of stelt de oriëntatie van de tekenrichtlijn in. Lezen/Schrijven [Orientation](../../com.aspose.slides/orientation).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getPosition() {#getPosition--}
```
public abstract float getPosition()
```

Geeft of stelt de positie van de tekenrichtlijn in punten vanaf de boven- en linkerhoek van de dia in. Lezen/Schrijven float.

--------------------

Het typische bereik van waarden is van nul tot de diahoogte voor een horizontale gids en van nul tot de dia-breedte voor een verticale gids.

**Retour:**
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```

Geeft of stelt de positie van de tekenrichtlijn in punten vanaf de boven- en linkerhoek van de dia in. Lezen/Schrijven float.

--------------------

Het typische bereik van waarden is van nul tot de diahoogte voor een horizontale gids en van nul tot de dia-breedte voor een verticale gids.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract Color getColor()
```

Geeft of stelt de kleur van de tekenrichtlijn in. Lezen/Schrijven java.awt.Color.

**Retour:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```

Geeft of stelt de kleur van de tekenrichtlijn in. Lezen/Schrijven java.awt.Color.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.awt.Color |  |
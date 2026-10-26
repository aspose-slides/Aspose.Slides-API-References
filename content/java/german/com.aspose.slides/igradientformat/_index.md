---
title: IGradientFormat
second_title: Aspose.Slides für Java API-Referenz
description: Stellt ein Farbverlaufsformat dar.
type: docs
url: /de/com.aspose.slides/igradientformat/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormat extends IFillParamSource
```

Stellt ein Farbverlaufformat dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | Gibt den Drehmodus für einen Farbverlauf zurück oder legt ihn fest. |
| [setTileFlip(int value)](#setTileFlip-int-) | Gibt den Drehmodus für einen Farbverlauf zurück oder legt ihn fest. |
| [getGradientDirection()](#getGradientDirection--) | Gibt den Stil eines Farbverlaufs zurück oder legt ihn fest. |
| [setGradientDirection(int value)](#setGradientDirection-int-) | Gibt den Stil eines Farbverlaufs zurück oder legt ihn fest. |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | Gibt den Winkel eines Farbverlaufs zurück oder legt ihn fest. |
| [setLinearGradientAngle(float value)](#setLinearGradientAngle-float-) | Gibt den Winkel eines Farbverlaufs zurück oder legt ihn fest. |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | Bestimmt, ob ein Farbverlauf skaliert wird. |
| [setLinearGradientScaled(byte value)](#setLinearGradientScaled-byte-) | Bestimmt, ob ein Farbverlauf skaliert wird. |
| [getGradientShape()](#getGradientShape--) | Gibt die Form eines Farbverlaufs zurück oder legt sie fest. |
| [setGradientShape(byte value)](#setGradientShape-byte-) | Gibt die Form eines Farbverlaufs zurück oder legt sie fest. |
| [getGradientStops()](#getGradientStops--) | Gibt die Sammlung von Farbverlaufspunkten zurück. |
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```

Gibt den Drehmodus für einen Farbverlauf zurück oder legt ihn fest. Lesen/Schreiben [TileFlip](../../com.aspose.slides/tileflip).

**Rückgabewert:**
int
### setTileFlip(int value) {#setTileFlip-int-}
```
public abstract void setTileFlip(int value)
```

Gibt den Drehmodus für einen Farbverlauf zurück oder legt ihn fest. Lesen/Schreiben [TileFlip](../../com.aspose.slides/tileflip).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```

Gibt den Stil eines Farbverlaufs zurück oder legt ihn fest. Lesen/Schreiben [GradientDirection](../../com.aspose.slides/gradientdirection).

**Rückgabewert:**
int
### setGradientDirection(int value) {#setGradientDirection-int-}
```
public abstract void setGradientDirection(int value)
```

Gibt den Stil eines Farbverlaufs zurück oder legt ihn fest. Lesen/Schreiben [GradientDirection](../../com.aspose.slides/gradientdirection).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```

Gibt den Winkel eines Farbverlaufs zurück oder legt ihn fest. Lesen/Schreiben float.

**Rückgabewert:**
float
### setLinearGradientAngle(float value) {#setLinearGradientAngle-float-}
```
public abstract void setLinearGradientAngle(float value)
```

Gibt den Winkel eines Farbverlaufs zurück oder legt ihn fest. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract byte getLinearGradientScaled()
```

Bestimmt, ob ein Farbverlauf skaliert wird. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabewert:**
byte
### setLinearGradientScaled(byte value) {#setLinearGradientScaled-byte-}
```
public abstract void setLinearGradientScaled(byte value)
```

Bestimmt, ob ein Farbverlauf skaliert wird. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```

Gibt die Form eines Farbverlaufs zurück oder legt sie fest. Lesen/Schreiben [GradientShape](../../com.aspose.slides/gradientshape).

**Rückgabewert:**
byte
### setGradientShape(byte value) {#setGradientShape-byte-}
```
public abstract void setGradientShape(byte value)
```

Gibt die Form eines Farbverlaufs zurück oder legt sie fest. Lesen/Schreiben [GradientShape](../../com.aspose.slides/gradientshape).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollection getGradientStops()
```

Gibt die Sammlung von Farbverlaufspunkten zurück. Nur lesen [IGradientStopCollection](../../com.aspose.slides/igradientstopcollection).

**Rückgabewert:**
[IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
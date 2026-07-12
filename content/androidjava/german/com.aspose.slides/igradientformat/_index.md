---
title: IGradientFormat
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt ein Farbverlaufsformat dar.
type: docs
url: /de/com.aspose.slides/igradientformat/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormat extends IFillParamSource
```

Stellt ein Farbverlaufsformat dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | Gibt den Flipping-Modus für einen Farbverlauf zurück oder setzt ihn. |
| [setTileFlip(int value)](#setTileFlip-int-) | Gibt den Flipping-Modus für einen Farbverlauf zurück oder setzt ihn. |
| [getGradientDirection()](#getGradientDirection--) | Gibt den Stil eines Farbverlaufs zurück oder setzt ihn. |
| [setGradientDirection(int value)](#setGradientDirection-int-) | Gibt den Stil eines Farbverlaufs zurück oder setzt ihn. |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | Gibt den Winkel eines Farbverlaufs zurück oder setzt ihn. |
| [setLinearGradientAngle(float value)](#setLinearGradientAngle-float-) | Gibt den Winkel eines Farbverlaufs zurück oder setzt ihn. |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | Bestimmt, ob ein Farbverlauf skaliert ist. |
| [setLinearGradientScaled(byte value)](#setLinearGradientScaled-byte-) | Bestimmt, ob ein Farbverlauf skaliert ist. |
| [getGradientShape()](#getGradientShape--) | Gibt die Form eines Farbverlaufs zurück oder setzt sie. |
| [setGradientShape(byte value)](#setGradientShape-byte-) | Gibt die Form eines Farbverlaufs zurück oder setzt sie. |
| [getGradientStops()](#getGradientStops--) | Gibt die Sammlung der Farbverlaufsstopps zurück. |
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```

Gibt den Flipping-Modus für einen Farbverlauf zurück oder setzt ihn. Lesen/Schreiben [TileFlip](../../com.aspose.slides/tileflip).

**Rückgabewert:**
int
### setTileFlip(int value) {#setTileFlip-int-}
```
public abstract void setTileFlip(int value)
```

Gibt den Flipping-Modus für einen Farbverlauf zurück oder setzt ihn. Lesen/Schreiben [TileFlip](../../com.aspose.slides/tileflip).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```

Gibt den Stil eines Farbverlaufs zurück oder setzt ihn. Lesen/Schreiben [GradientDirection](../../com.aspose.slides/gradientdirection).

**Rückgabewert:**
int
### setGradientDirection(int value) {#setGradientDirection-int-}
```
public abstract void setGradientDirection(int value)
```

Gibt den Stil eines Farbverlaufs zurück oder setzt ihn. Lesen/Schreiben [GradientDirection](../../com.aspose.slides/gradientdirection).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```

Gibt den Winkel eines Farbverlaufs zurück oder setzt ihn. Lesen/Schreiben float.

**Rückgabewert:**
float
### setLinearGradientAngle(float value) {#setLinearGradientAngle-float-}
```
public abstract void setLinearGradientAngle(float value)
```

Gibt den Winkel eines Farbverlaufs zurück oder setzt ihn. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract byte getLinearGradientScaled()
```

Bestimmt, ob ein Farbverlauf skaliert ist. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabewert:**
byte
### setLinearGradientScaled(byte value) {#setLinearGradientScaled-byte-}
```
public abstract void setLinearGradientScaled(byte value)
```

Bestimmt, ob ein Farbverlauf skaliert ist. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```

Gibt die Form eines Farbverlaufs zurück oder setzt sie. Lesen/Schreiben [GradientShape](../../com.aspose.slides/gradientshape).

**Rückgabewert:**
byte
### setGradientShape(byte value) {#setGradientShape-byte-}
```
public abstract void setGradientShape(byte value)
```

Gibt die Form eines Farbverlaufs zurück oder setzt sie. Lesen/Schreiben [GradientShape](../../com.aspose.slides/gradientshape).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollection getGradientStops()
```

Gibt die Sammlung der Farbverlaufsstopps zurück. Nur Lesen [IGradientStopCollection](../../com.aspose.slides/igradientstopcollection).

**Rückgabewert:**
[IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
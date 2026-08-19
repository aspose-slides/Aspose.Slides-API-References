---
title: IGradientFormat
second_title: Aspose.Slides pro Java referenční příručka API
description: Zastupuje formát gradientu.
type: docs
url: /cs/com.aspose.slides/igradientformat/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormat extends IFillParamSource
```

Zastupuje formát gradientu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | Returns or sets the flipping mode for a gradient. |
| [setTileFlip(int value)](#setTileFlip-int-) | Returns or sets the flipping mode for a gradient. |
| [getGradientDirection()](#getGradientDirection--) | Returns or sets the style of a gradient. |
| [setGradientDirection(int value)](#setGradientDirection-int-) | Returns or sets the style of a gradient. |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | Returns or sets the angle of a gradient. |
| [setLinearGradientAngle(float value)](#setLinearGradientAngle-float-) | Returns or sets the angle of a gradient. |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | Determines whether a gradient is scaled. |
| [setLinearGradientScaled(byte value)](#setLinearGradientScaled-byte-) | Determines whether a gradient is scaled. |
| [getGradientShape()](#getGradientShape--) | Returns or sets the shape of a gradient. |
| [setGradientShape(byte value)](#setGradientShape-byte-) | Returns or sets the shape of a gradient. |
| [getGradientStops()](#getGradientStops--) | Returns the collection of gradient stops. |
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```

Vrací nebo nastavuje režim otáčení pro gradient. Čtení/zápis [TileFlip](../../com.aspose.slides/tileflip).

**Vrací:**
int
### setTileFlip(int value) {#setTileFlip-int-}
```
public abstract void setTileFlip(int value)
```

Vrací nebo nastavuje režim otáčení pro gradient. Čtení/zápis [TileFlip](../../com.aspose.slides/tileflip).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```

Vrací nebo nastavuje styl gradientu. Čtení/zápis [GradientDirection](../../com.aspose.slides/gradientdirection).

**Vrací:**
int
### setGradientDirection(int value) {#setGradientDirection-int-}
```
public abstract void setGradientDirection(int value)
```

Vrací nebo nastavuje styl gradientu. Čtení/zápis [GradientDirection](../../com.aspose.slides/gradientdirection).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```

Vrací nebo nastavuje úhel gradientu. Čtení/zápis float.

**Vrací:**
float
### setLinearGradientAngle(float value) {#setLinearGradientAngle-float-}
```
public abstract void setLinearGradientAngle(float value)
```

Vrací nebo nastavuje úhel gradientu. Čtení/zápis float.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract byte getLinearGradientScaled()
```

Určuje, zda je gradient škálován. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte
### setLinearGradientScaled(byte value) {#setLinearGradientScaled-byte-}
```
public abstract void setLinearGradientScaled(byte value)
```

Určuje, zda je gradient škálován. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```

Vrací nebo nastavuje tvar gradientu. Čtení/zápis [GradientShape](../../com.aspose.slides/gradientshape).

**Vrací:**
byte
### setGradientShape(byte value) {#setGradientShape-byte-}
```
public abstract void setGradientShape(byte value)
```

Vrací nebo nastavuje tvar gradientu. Čtení/zápis [GradientShape](../../com.aspose.slides/gradientshape).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollection getGradientStops()
```

Vrací kolekci zastavení gradientu. Pouze ke čtení [IGradientStopCollection](../../com.aspose.slides/igradientstopcollection).

**Vrací:**
[IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
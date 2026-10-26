---
title: IGradientFormat
second_title: Aspose.Slides pro Android přes Java API Reference
description: Reprezentuje formát gradientu.
type: docs
url: /cs/com.aspose.slides/igradientformat/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormat extends IFillParamSource
```

Reprezentuje formát gradientu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | Vrací nebo nastavuje režim otáčení gradientu. |
| [setTileFlip(int value)](#setTileFlip-int-) | Vrací nebo nastavuje režim otáčení gradientu. |
| [getGradientDirection()](#getGradientDirection--) | Vrací nebo nastavuje styl gradientu. |
| [setGradientDirection(int value)](#setGradientDirection-int-) | Vrací nebo nastavuje styl gradientu. |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | Vrací nebo nastavuje úhel gradientu. |
| [setLinearGradientAngle(float value)](#setLinearGradientAngle-float-) | Vrací nebo nastavuje úhel gradientu. |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | Určuje, zda je gradient škálován. |
| [setLinearGradientScaled(byte value)](#setLinearGradientScaled-byte-) | Určuje, zda je gradient škálován. |
| [getGradientShape()](#getGradientShape--) | Vrací nebo nastavuje tvar gradientu. |
| [setGradientShape(byte value)](#setGradientShape-byte-) | Vrací nebo nastavuje tvar gradientu. |
| [getGradientStops()](#getGradientStops--) | Vrací kolekci zastávek gradientu. |
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```


Vrací nebo nastavuje režim otáčení gradientu. Čtení/Zápis [TileFlip](../../com.aspose.slides/tileflip).

**Vrací:**
int
### setTileFlip(int value) {#setTileFlip-int-}
```
public abstract void setTileFlip(int value)
```


Vrací nebo nastavuje režim otáčení gradientu. Čtení/Zápis [TileFlip](../../com.aspose.slides/tileflip).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```


Vrací nebo nastavuje styl gradientu. Čtení/Zápis [GradientDirection](../../com.aspose.slides/gradientdirection).

**Vrací:**
int
### setGradientDirection(int value) {#setGradientDirection-int-}
```
public abstract void setGradientDirection(int value)
```


Vrací nebo nastavuje styl gradientu. Čtení/Zápis [GradientDirection](../../com.aspose.slides/gradientdirection).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```


Vrací nebo nastavuje úhel gradientu. Čtení/Zápis float.

**Vrací:**
float
### setLinearGradientAngle(float value) {#setLinearGradientAngle-float-}
```
public abstract void setLinearGradientAngle(float value)
```


Vrací nebo nastavuje úhel gradientu. Čtení/Zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract byte getLinearGradientScaled()
```


Určuje, zda je gradient škálován. Čtení/Zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte
### setLinearGradientScaled(byte value) {#setLinearGradientScaled-byte-}
```
public abstract void setLinearGradientScaled(byte value)
```


Určuje, zda je gradient škálován. Čtení/Zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```


Vrací nebo nastavuje tvar gradientu. Čtení/Zápis [GradientShape](../../com.aspose.slides/gradientshape).

**Vrací:**
byte
### setGradientShape(byte value) {#setGradientShape-byte-}
```
public abstract void setGradientShape(byte value)
```


Vrací nebo nastavuje tvar gradientu. Čtení/Zápis [GradientShape](../../com.aspose.slides/gradientshape).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollection getGradientStops()
```


Vrací kolekci zastávek gradientu. Pouze ke čtení [IGradientStopCollection](../../com.aspose.slides/igradientstopcollection).

**Vrací:**
[IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
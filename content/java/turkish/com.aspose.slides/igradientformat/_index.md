---
title: IGradientFormat
second_title: Aspose.Slides for Java API Referansı
description: Bir gradient formatını temsil eder.
type: docs
url: /tr/com.aspose.slides/igradientformat/
---
**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormat extends IFillParamSource
```

Bir gradient formatını temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | Bir gradient için çevirme modunu alır veya ayarlar. |
| [setTileFlip(int value)](#setTileFlip-int-) | Bir gradient için çevirme modunu alır veya ayarlar. |
| [getGradientDirection()](#getGradientDirection--) | Bir gradient için stilini alır veya ayarlar. |
| [setGradientDirection(int value)](#setGradientDirection-int-) | Bir gradient için stilini alır veya ayarlar. |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | Bir gradient için açıyı alır veya ayarlar. |
| [setLinearGradientAngle(float value)](#setLinearGradientAngle-float-) | Bir gradient için açıyı alır veya ayarlar. |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | Bir gradient'in ölçeklenip ölçeklenmediğini belirler. |
| [setLinearGradientScaled(byte value)](#setLinearGradientScaled-byte-) | Bir gradient'in ölçeklenip ölçeklenmediğini belirler. |
| [getGradientShape()](#getGradientShape--) | Bir gradient'in şeklini alır veya ayarlar. |
| [setGradientShape(byte value)](#setGradientShape-byte-) | Bir gradient'in şeklini alır veya ayarlar. |
| [getGradientStops()](#getGradientStops--) | Gradient duraklarının koleksiyonunu döndürür. |
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```


Bir gradient için çevirme modunu alır veya ayarlar. Okuma/Yazma [TileFlip](../../com.aspose.slides/tileflip).

**Döndürür:**
int
### setTileFlip(int value) {#setTileFlip-int-}
```
public abstract void setTileFlip(int value)
```


Bir gradient için çevirme modunu alır veya ayarlar. Okuma/Yazma [TileFlip](../../com.aspose.slides/tileflip).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```


Bir gradient için stilini alır veya ayarlar. Okuma/Yazma [GradientDirection](../../com.aspose.slides/gradientdirection).

**Döndürür:**
int
### setGradientDirection(int value) {#setGradientDirection-int-}
```
public abstract void setGradientDirection(int value)
```


Bir gradient için stilini alır veya ayarlar. Okuma/Yazma [GradientDirection](../../com.aspose.slides/gradientdirection).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```


Bir gradient için açıyı alır veya ayarlar. Okuma/Yazma float.

**Döndürür:**
float
### setLinearGradientAngle(float value) {#setLinearGradientAngle-float-}
```
public abstract void setLinearGradientAngle(float value)
```


Bir gradient için açıyı alır veya ayarlar. Okuma/Yazma float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract byte getLinearGradientScaled()
```


Bir gradient'in ölçeklenip ölçeklenmediğini belirler. Okuma/Yazma [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte
### setLinearGradientScaled(byte value) {#setLinearGradientScaled-byte-}
```
public abstract void setLinearGradientScaled(byte value)
```


Bir gradient'in ölçeklenip ölçeklenmediğini belirler. Okuma/Yazma [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```


Bir gradient'in şeklini alır veya ayarlar. Okuma/Yazma [GradientShape](../../com.aspose.slides/gradientshape).

**Döndürür:**
byte
### setGradientShape(byte value) {#setGradientShape-byte-}
```
public abstract void setGradientShape(byte value)
```


Bir gradient'in şeklini alır veya ayarlar. Okuma/Yazma [GradientShape](../../com.aspose.slides/gradientshape).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollection getGradientStops()
```


Gradient duraklarının koleksiyonunu döndürür. Yalnızca okuma [IGradientStopCollection](../../com.aspose.slides/igradientstopcollection).

**Döndürür:**
[IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
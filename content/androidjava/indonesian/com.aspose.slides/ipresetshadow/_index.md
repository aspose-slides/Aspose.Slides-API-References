---
title: IPresetShadow
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili efek Bayangan Preset.
type: docs
url: /id/com.aspose.slides/ipresetshadow/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IPresetShadow extends IImageTransformOperation, IAccessiblePVIObject<IPresetShadowEffectiveData>
```

Mewakili efek Bayangan Preset.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getDirection()](#getDirection--) | Arah bayangan. |
| [setDirection(float value)](#setDirection-float-) | Arah bayangan. |
| [getDistance()](#getDistance--) | Jarak bayangan. |
| [setDistance(double value)](#setDistance-double-) | Jarak bayangan. |
| [getShadowColor()](#getShadowColor--) | Warna bayangan. |
| [getPreset()](#getPreset--) | Preset. |
| [setPreset(int value)](#setPreset-int-) | Preset. |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```


Arah bayangan. Baca/tulis float.

**Mengembalikan:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```


Arah bayangan. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```


Jarak bayangan. Baca/tulis double.

**Mengembalikan:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```


Jarak bayangan. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```


Warna bayangan. Hanya-baca [IColorFormat](../../com.aspose.slides/icolorformat).

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public abstract int getPreset()
```


Preset. Baca/tulis [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Mengembalikan:**
int
### setPreset(int value) {#setPreset-int-}
```
public abstract void setPreset(int value)
```


Preset. Baca/tulis [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
---
title: IImageTransformOperationFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create image effects instances
type: docs
url: /id/com.aspose.slides/iimagetransformoperationfactory/
---```
public interface IImageTransformOperationFactory
```

Memungkinkan membuat instance efek gambar

--------------------

Untuk antarmuka COM.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | Membuat efek Alpha BiLevel. |
| [createAlphCeiling()](#createAlphCeiling--) | Membuat efek Alpha Ceiling. |
| [createAlphaFloor()](#createAlphaFloor--) | Membuat efek Alpha floor. |
| [createAlphaInverse()](#createAlphaInverse--) | Membuat efek Alpha inverse. |
| [createAlphaModulate()](#createAlphaModulate--) | Membuat efek Alpha modulate. |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | Membuat efek Alpha modulate fixed. |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | Membuat efek Alpha replace. |
| [createBiLevel(float threshold)](#createBiLevel-float-) | Membuat efek BiLevel. |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | Membuat efek Blur. |
| [createColorChange()](#createColorChange--) | Membuat efek Color change. |
| [createColorReplace()](#createColorReplace--) | Membuat efek Color replace. |
| [createDuotone()](#createDuotone--) | Membuat efek Duotone. |
| [createFillOverlay()](#createFillOverlay--) | Membuat efek Fill overlay. |
| [createGrayScale()](#createGrayScale--) | Membuat efek Gray scale. |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | Membuat efek Hue Saturation Luminance. |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | Membuat efek Luminance. |
| [createTint(float hue, float amount)](#createTint-float-float-) | Membuat efek Tint. |
### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public abstract IAlphaBiLevel createAlphaBiLevel(float threshold)
```


Membuat efek Alpha BiLevel.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threshold | float | Threshold. |

**Mengembalikan:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Alpha BiLevel efek.
### createAlphCeiling() {#createAlphCeiling--}
```
public abstract IAlphaCeiling createAlphCeiling()
```


Membuat efek Alpha Ceiling.

**Mengembalikan:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Alpha Ceiling efek.
### createAlphaFloor() {#createAlphaFloor--}
```
public abstract IAlphaFloor createAlphaFloor()
```


Membuat efek Alpha floor.

**Mengembalikan:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Alpha floor efek.
### createAlphaInverse() {#createAlphaInverse--}
```
public abstract IAlphaInverse createAlphaInverse()
```


Membuat efek Alpha inverse.

**Mengembalikan:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Alpha inverst efek.
### createAlphaModulate() {#createAlphaModulate--}
```
public abstract IAlphaModulate createAlphaModulate()
```


Membuat efek Alpha modulate.

**Mengembalikan:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Alpha modulate efek.
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public abstract IAlphaModulateFixed createAlphaModulateFixed(float amount)
```


Membuat efek Alpha modulate fixed.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| amount | float | Amount. |

**Mengembalikan:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Alpha modulate fixed efek.
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public abstract IAlphaReplace createAlphaReplace(float alpha)
```


Membuat efek Alpha replace.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| alpha | float | Alpha |

**Mengembalikan:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Alpha replace efek.
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public abstract IBiLevel createBiLevel(float threshold)
```


Membuat efek BiLevel.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threshold | float | Threshold. |

**Mengembalikan:**
[IBiLevel](../../com.aspose.slides/ibilevel) - BiLevel efek.
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public abstract IBlur createBlur(double radius, boolean grow)
```


Membuat efek Blur.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| radius | double | Radius. |
| grow | boolean | Grow. |

**Mengembalikan:**
[IBlur](../../com.aspose.slides/iblur) - Blur efek.
### createColorChange() {#createColorChange--}
```
public abstract IColorChange createColorChange()
```


Membuat efek Color change.

**Mengembalikan:**
[IColorChange](../../com.aspose.slides/icolorchange) - Color change efek.
### createColorReplace() {#createColorReplace--}
```
public abstract IColorReplace createColorReplace()
```


Membuat efek Color replace.

**Mengembalikan:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Color replace efek.
### createDuotone() {#createDuotone--}
```
public abstract IDuotone createDuotone()
```


Membuat efek Duotone.

**Mengembalikan:**
[IDuotone](../../com.aspose.slides/iduotone) - Duotone efek.
### createFillOverlay() {#createFillOverlay--}
```
public abstract IFillOverlay createFillOverlay()
```


Membuat efek Fill overlay.

**Mengembalikan:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Fill overlay efek.
### createGrayScale() {#createGrayScale--}
```
public abstract IGrayScale createGrayScale()
```


Membuat efek Gray scale.

**Mengembalikan:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Returns gray scale efek.
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public abstract IHSL createHSL(float hue, float saturation, float luminance)
```


Membuat efek Hue Saturation Luminance.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| hue | float | Hue. |
| saturation | float | Saturation. |
| luminance | float | Luminance. |

**Mengembalikan:**
[IHSL](../../com.aspose.slides/ihsl) - HSL efek.
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public abstract ILuminance createLuminance(float brightness, float contrast)
```


Membuat efek Luminance.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| brightness | float | Brightness. |
| contrast | float | Contrast. |

**Mengembalikan:**
[ILuminance](../../com.aspose.slides/iluminance) - Luminance efek.
### createTint(float hue, float amount) {#createTint-float-float-}
```
public abstract ITint createTint(float hue, float amount)
```


Membuat efek Tint.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| hue | float | Hue. |
| amount | float | Amount. |

**Mengembalikan:**
[ITint](../../com.aspose.slides/itint) - Tint efek.
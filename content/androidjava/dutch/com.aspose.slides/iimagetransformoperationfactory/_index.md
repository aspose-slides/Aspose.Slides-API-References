---
title: IImageTransformOperationFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Staat toe om instanties van beeldeffecten te maken
type: docs
url: /nl/com.aspose.slides/iimagetransformoperationfactory/
---```
public interface IImageTransformOperationFactory
```

Staat toe om instanties van beeldeffecten te maken

--------------------

For COM interface.
## Methods

| Methode | Beschrijving |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | Creëert Alpha BiLevel-effect. |
| [createAlphCeiling()](#createAlphCeiling--) | Creëert Alpha Ceiling-effect. |
| [createAlphaFloor()](#createAlphaFloor--) | Creëert Alpha floor-effect. |
| [createAlphaInverse()](#createAlphaInverse--) | Creëert Alpha inverse-effect. |
| [createAlphaModulate()](#createAlphaModulate--) | Creëert Alpha modulate-effect. |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | Creëert Alpha modulate fixed-effect. |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | Creëert Alpha replace-effect. |
| [createBiLevel(float threshold)](#createBiLevel-float-) | Creëert BiLevel-effect. |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | Creëert Blur-effect. |
| [createColorChange()](#createColorChange--) | Creëert Color change-effect. |
| [createColorReplace()](#createColorReplace--) | Creëert Color replace-effect. |
| [createDuotone()](#createDuotone--) | Creëert Duotone-effect. |
| [createFillOverlay()](#createFillOverlay--) | Creëert Fill overlay-effect. |
| [createGrayScale()](#createGrayScale--) | Creëert Gray scale-effect. |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | Creëert Hue Saturation Luminance-effect. |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | Creëert Luminance-effect. |
| [createTint(float hue, float amount)](#createTint-float-float-) | Creëert Tint-effect. |
### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public abstract IAlphaBiLevel createAlphaBiLevel(float threshold)
```

Creëert Alpha BiLevel-effect.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| threshold | float | Drempel. |

**Retour:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Alpha BiLevel-effect.
### createAlphCeiling() {#createAlphCeiling--}
```
public abstract IAlphaCeiling createAlphCeiling()
```

Creëert Alpha Ceiling-effect.

**Retour:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Alpha Ceiling-effect.
### createAlphaFloor() {#createAlphaFloor--}
```
public abstract IAlphaFloor createAlphaFloor()
```

Creëert Alpha floor-effect.

**Retour:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Alpha floor-effect.
### createAlphaInverse() {#createAlphaInverse--}
```
public abstract IAlphaInverse createAlphaInverse()
```

Creëert Alpha inverse-effect.

**Retour:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Alpha inverst effect.
### createAlphaModulate() {#createAlphaModulate--}
```
public abstract IAlphaModulate createAlphaModulate()
```

Creëert Alpha modulate-effect.

**Retour:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Alpha modulate-effect.
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public abstract IAlphaModulateFixed createAlphaModulateFixed(float amount)
```

Creëert Alpha modulate fixed-effect.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| amount | float | Hoeveelheid. |

**Retour:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Alpha modulate fixed-effect.
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public abstract IAlphaReplace createAlphaReplace(float alpha)
```

Creëert Alpha replace-effect.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| alpha | float | Alpha |

**Retour:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Alpha replace-effect.
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public abstract IBiLevel createBiLevel(float threshold)
```

Creëert BiLevel-effect.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| threshold | float | Drempel. |

**Retour:**
[IBiLevel](../../com.aspose.slides/ibilevel) - BiLevel-effect.
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public abstract IBlur createBlur(double radius, boolean grow)
```

Creëert Blur-effect.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| radius | double | Radius. |
| grow | boolean | Groei. |

**Retour:**
[IBlur](../../com.aspose.slides/iblur) - Blur-effect.
### createColorChange() {#createColorChange--}
```
public abstract IColorChange createColorChange()
```

Creëert Color change-effect.

**Retour:**
[IColorChange](../../com.aspose.slides/icolorchange) - Color change-effect.
### createColorReplace() {#createColorReplace--}
```
public abstract IColorReplace createColorReplace()
```

Creëert Color replace-effect.

**Retour:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Color replace-effect.
### createDuotone() {#createDuotone--}
```
public abstract IDuotone createDuotone()
```

Creëert Duotone-effect.

**Retour:**
[IDuotone](../../com.aspose.slides/iduotone) - Duotone-effect.
### createFillOverlay() {#createFillOverlay--}
```
public abstract IFillOverlay createFillOverlay()
```

Creëert Fill overlay-effect.

**Retour:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Fill overlay-effect.
### createGrayScale() {#createGrayScale--}
```
public abstract IGrayScale createGrayScale()
```

Creëert Gray scale-effect.

**Retour:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Returns gray scale effect.
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public abstract IHSL createHSL(float hue, float saturation, float luminance)
```

Creëert Hue Saturation Luminance-effect.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hue | float | Hue. |
| saturation | float | Saturation. |
| luminance | float | Luminance. |

**Retour:**
[IHSL](../../com.aspose.slides/ihsl) - HSL-effect.
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public abstract ILuminance createLuminance(float brightness, float contrast)
```

Creëert Luminance-effect.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brightness | float | Brightness. |
| contrast | float | Contrast. |

**Retour:**
[ILuminance](../../com.aspose.slides/iluminance) - Luminance-effect.
### createTint(float hue, float amount) {#createTint-float-float-}
```
public abstract ITint createTint(float hue, float amount)
```

Creëert Tint-effect.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hue | float | Hue. |
| amount | float | Hoeveelheid. |

**Retour:**
[ITint](../../com.aspose.slides/itint) - Tint-effect.
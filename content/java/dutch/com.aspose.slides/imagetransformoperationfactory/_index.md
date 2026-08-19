---
title: ImageTransformOperationFactory
second_title: Aspose.Slides voor Java API-referentie
description: Staat toe om beeldtransformatie-operaties te maken
type: docs
url: /nl/com.aspose.slides/imagetransformoperationfactory/
---
**Erfelijkheid:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory)
```
public class ImageTransformOperationFactory implements IImageTransformOperationFactory
```

Staat toe om beeldtransformatie-operaties te maken

--------------------

Voor COM-compatibiliteit.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ImageTransformOperationFactory()](#ImageTransformOperationFactory--) |  |
## Methods

| Method | Beschrijving |
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
### ImageTransformOperationFactory() {#ImageTransformOperationFactory--}
```
public ImageTransformOperationFactory()
```

### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public final IAlphaBiLevel createAlphaBiLevel(float threshold)
```

Creëert Alpha BiLevel-effect.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| threshold | float | Drempel. |

**Returns:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Alpha BiLevel-effect.
### createAlphCeiling() {#createAlphCeiling--}
```
public final IAlphaCeiling createAlphCeiling()
```

Creëert Alpha Ceiling-effect.

**Returns:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Alpha Ceiling-effect.
### createAlphaFloor() {#createAlphaFloor--}
```
public final IAlphaFloor createAlphaFloor()
```

Creëert Alpha floor-effect.

**Returns:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Alpha floor-effect.
### createAlphaInverse() {#createAlphaInverse--}
```
public final IAlphaInverse createAlphaInverse()
```

Creëert Alpha inverse-effect.

**Returns:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Alpha inverst-effect.
### createAlphaModulate() {#createAlphaModulate--}
```
public final IAlphaModulate createAlphaModulate()
```

Creëert Alpha modulate-effect.

**Returns:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Alpha modulate-effect.
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public final IAlphaModulateFixed createAlphaModulateFixed(float amount)
```

Creëert Alpha modulate fixed-effect.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| amount | float | Hoeveelheid. |

**Returns:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Alpha modulate fixed-effect.
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public final IAlphaReplace createAlphaReplace(float alpha)
```

Creëert Alpha replace-effect.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| alpha | float | Alpha |

**Returns:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Alpha replace-effect.
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public final IBiLevel createBiLevel(float threshold)
```

Creëert BiLevel-effect.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| threshold | float | Drempel. |

**Returns:**
[IBiLevel](../../com.aspose.slides/ibilevel) - BiLevel-effect.
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public final IBlur createBlur(double radius, boolean grow)
```

Creëert Blur-effect.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| radius | double | Straal. |
| grow | boolean | Groei. |

**Returns:**
[IBlur](../../com.aspose.slides/iblur) - Blur-effect.
### createColorChange() {#createColorChange--}
```
public final IColorChange createColorChange()
```

Creëert Color change-effect.

**Returns:**
[IColorChange](../../com.aspose.slides/icolorchange) - Color change-effect.
### createColorReplace() {#createColorReplace--}
```
public final IColorReplace createColorReplace()
```

Creëert Color replace-effect.

**Returns:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Color replace-effect.
### createDuotone() {#createDuotone--}
```
public final IDuotone createDuotone()
```

Creëert Duotone-effect.

**Returns:**
[IDuotone](../../com.aspose.slides/iduotone) - Duotone-effect.
### createFillOverlay() {#createFillOverlay--}
```
public final IFillOverlay createFillOverlay()
```

Creëert Fill overlay-effect.

**Returns:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Fill overlay-effect.
### createGrayScale() {#createGrayScale--}
```
public final IGrayScale createGrayScale()
```

Creëert Gray scale-effect.

**Returns:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Gray scale-effect.
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public final IHSL createHSL(float hue, float saturation, float luminance)
```

Creëert Hue Saturation Luminance-effect.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hue | float | Hue. |
| saturation | float | Saturation. |
| luminance | float | Luminance. |

**Returns:**
[IHSL](../../com.aspose.slides/ihsl) - HSL-effect.
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public final ILuminance createLuminance(float brightness, float contrast)
```

Creëert Luminance-effect.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brightness | float | Helderheid. |
| contrast | float | Contrast. |

**Returns:**
[ILuminance](../../com.aspose.slides/iluminance) - Luminance-effect.
### createTint(float hue, float amount) {#createTint-float-float-}
```
public final ITint createTint(float hue, float amount)
```

Creëert Tint-effect.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hue | float | Hue. |
| amount | float | Hoeveelheid. |

**Returns:**
[ITint](../../com.aspose.slides/itint) - Tint-effect.
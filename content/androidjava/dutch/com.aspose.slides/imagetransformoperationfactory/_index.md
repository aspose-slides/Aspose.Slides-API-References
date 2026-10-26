---
title: ImageTransformOperationFactory
second_title: Aspose.Slides voor Android via Java API-referentie
description: Staat toe om beeldtransformatie-operaties te maken
type: docs
url: /nl/com.aspose.slides/imagetransformoperationfactory/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory)
```
public class ImageTransformOperationFactory implements IImageTransformOperationFactory
```

Staat toe om beeldtransformatie-operaties te maken

--------------------

Voor COM-compatibiliteit.
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [ImageTransformOperationFactory()](#ImageTransformOperationFactory--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | Maakt Alpha BiLevel effect. |
| [createAlphCeiling()](#createAlphCeiling--) | Maakt Alpha Ceiling effect. |
| [createAlphaFloor()](#createAlphaFloor--) | Maakt Alpha floor effect. |
| [createAlphaInverse()](#createAlphaInverse--) | Maakt Alpha inverse effect. |
| [createAlphaModulate()](#createAlphaModulate--) | Maakt Alpha modulate effect. |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | Maakt Alpha modulate fixed effect. |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | Maakt Alpha replace effect. |
| [createBiLevel(float threshold)](#createBiLevel-float-) | Maakt BiLevel effect. |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | Maakt Blur effect. |
| [createColorChange()](#createColorChange--) | Maakt Color change effect. |
| [createColorReplace()](#createColorReplace--) | Maakt Color replace effect. |
| [createDuotone()](#createDuotone--) | Maakt Duotone effect. |
| [createFillOverlay()](#createFillOverlay--) | Maakt Fill overlay effect. |
| [createGrayScale()](#createGrayScale--) | Maakt Gray scale effect. |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | Maakt Hue Saturation Luminance effect. |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | Maakt Luminance effect. |
| [createTint(float hue, float amount)](#createTint-float-float-) | Maakt Tint effect. |
### ImageTransformOperationFactory() {#ImageTransformOperationFactory--}
```
public ImageTransformOperationFactory()
```


### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public final IAlphaBiLevel createAlphaBiLevel(float threshold)
```


Maakt Alpha BiLevel effect.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| threshold | float | Drempelwaarde. |

**Retourwaarde:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Alpha BiLevel effect.
### createAlphCeiling() {#createAlphCeiling--}
```
public final IAlphaCeiling createAlphCeiling()
```


Maakt Alpha Ceiling effect.

**Retourwaarde:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Alpha Ceiling effect.
### createAlphaFloor() {#createAlphaFloor--}
```
public final IAlphaFloor createAlphaFloor()
```


Maakt Alpha floor effect.

**Retourwaarde:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Alpha floor effect.
### createAlphaInverse() {#createAlphaInverse--}
```
public final IAlphaInverse createAlphaInverse()
```


Maakt Alpha inverse effect.

**Retourwaarde:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Alpha inverst effect.
### createAlphaModulate() {#createAlphaModulate--}
```
public final IAlphaModulate createAlphaModulate()
```


Maakt Alpha modulate effect.

**Retourwaarde:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Alpha modulate effect.
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public final IAlphaModulateFixed createAlphaModulateFixed(float amount)
```


Maakt Alpha modulate fixed effect.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| amount | float | Hoeveelheid. |

**Retourwaarde:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Alpha modulate fixed effect.
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public final IAlphaReplace createAlphaReplace(float alpha)
```


Maakt Alpha replace effect.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| alpha | float | Alpha |

**Retourwaarde:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Alpha replace effect.
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public final IBiLevel createBiLevel(float threshold)
```


Maakt BiLevel effect.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| threshold | float | Drempelwaarde. |

**Retourwaarde:**
[IBiLevel](../../com.aspose.slides/ibilevel) - BiLevel effect.
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public final IBlur createBlur(double radius, boolean grow)
```


Maakt Blur effect.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| radius | double | Straal. |
| grow | boolean | Groei. |

**Retourwaarde:**
[IBlur](../../com.aspose.slides/iblur) - Blur effect.
### createColorChange() {#createColorChange--}
```
public final IColorChange createColorChange()
```


Maakt Color change effect.

**Retourwaarde:**
[IColorChange](../../com.aspose.slides/icolorchange) - Color change effect.
### createColorReplace() {#createColorReplace--}
```
public final IColorReplace createColorReplace()
```


Maakt Color replace effect.

**Retourwaarde:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Color replace effect.
### createDuotone() {#createDuotone--}
```
public final IDuotone createDuotone()
```


Maakt Duotone effect.

**Retourwaarde:**
[IDuotone](../../com.aspose.slides/iduotone) - Duotone effect.
### createFillOverlay() {#createFillOverlay--}
```
public final IFillOverlay createFillOverlay()
```


Maakt Fill overlay effect.

**Retourwaarde:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Fill overlay effect.
### createGrayScale() {#createGrayScale--}
```
public final IGrayScale createGrayScale()
```


Maakt Gray scale effect.

**Retourwaarde:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Returns gray scale effect.
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public final IHSL createHSL(float hue, float saturation, float luminance)
```


Maakt Hue Saturation Luminance effect.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hue | float | Hue. |
| saturation | float | Saturation. |
| luminance | float | Luminance. |

**Retourwaarde:**
[IHSL](../../com.aspose.slides/ihsl) - HSL effect.
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public final ILuminance createLuminance(float brightness, float contrast)
```


Maakt Luminance effect.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| brightness | float | Helderheid. |
| contrast | float | Contrast. |

**Retourwaarde:**
[ILuminance](../../com.aspose.slides/iluminance) - Luminance effect.
### createTint(float hue, float amount) {#createTint-float-float-}
```
public final ITint createTint(float hue, float amount)
```


Maakt Tint effect.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hue | float | Hue. |
| amount | float | Hoeveelheid. |

**Retourwaarde:**
[ITint](../../com.aspose.slides/itint) - Tint effect.
---
title: ImageTransformOperationFactory
second_title: Aspose.Slides pour Android via la référence API Java
description: Permet de créer des opérations de transformation d'image
type: docs
url: /fr/com.aspose.slides/imagetransformoperationfactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory)
```
public class ImageTransformOperationFactory implements IImageTransformOperationFactory
```

Permet de créer des opérations de transformation d'image

--------------------

Pour la compatibilité COM.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ImageTransformOperationFactory()](#ImageTransformOperationFactory--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | Crée l'effet Alpha BiLevel. |
| [createAlphCeiling()](#createAlphCeiling--) | Crée l'effet Alpha Ceiling. |
| [createAlphaFloor()](#createAlphaFloor--) | Crée l'effet Alpha floor. |
| [createAlphaInverse()](#createAlphaInverse--) | Crée l'effet Alpha inverse. |
| [createAlphaModulate()](#createAlphaModulate--) | Crée l'effet Alpha modulate. |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | Crée l'effet Alpha modulate fixed. |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | Crée l'effet Alpha replace. |
| [createBiLevel(float threshold)](#createBiLevel-float-) | Crée l'effet BiLevel. |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | Crée l'effet Blur. |
| [createColorChange()](#createColorChange--) | Crée l'effet Color change. |
| [createColorReplace()](#createColorReplace--) | Crée l'effet Color replace. |
| [createDuotone()](#createDuotone--) | Crée l'effet Duotone. |
| [createFillOverlay()](#createFillOverlay--) | Crée l'effet Fill overlay. |
| [createGrayScale()](#createGrayScale--) | Crée l'effet Gray scale. |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | Crée l'effet Hue Saturation Luminance. |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | Crée l'effet Luminance. |
| [createTint(float hue, float amount)](#createTint-float-float-) | Crée l'effet Tint. |
### ImageTransformOperationFactory() {#ImageTransformOperationFactory--}
```
public ImageTransformOperationFactory()
```


### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public final IAlphaBiLevel createAlphaBiLevel(float threshold)
```


Crée l'effet Alpha BiLevel.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| threshold | float | Seuil. |

**Retour:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Alpha BiLevel effect.
### createAlphCeiling() {#createAlphCeiling--}
```
public final IAlphaCeiling createAlphCeiling()
```


Crée l'effet Alpha Ceiling.

**Retour:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Alpha Ceiling effect.
### createAlphaFloor() {#createAlphaFloor--}
```
public final IAlphaFloor createAlphaFloor()
```


Crée l'effet Alpha floor.

**Retour:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Alpha floor effect.
### createAlphaInverse() {#createAlphaInverse--}
```
public final IAlphaInverse createAlphaInverse()
```


Crée l'effet Alpha inverse.

**Retour:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Alpha inverst effect.
### createAlphaModulate() {#createAlphaModulate--}
```
public final IAlphaModulate createAlphaModulate()
```


Crée l'effet Alpha modulate.

**Retour:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Alpha modulate effect.
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public final IAlphaModulateFixed createAlphaModulateFixed(float amount)
```


Crée l'effet Alpha modulate fixed.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| amount | float | Quantité. |

**Retour:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Alpha modulate fixed effect.
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public final IAlphaReplace createAlphaReplace(float alpha)
```


Crée l'effet Alpha replace.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| alpha | float | Alpha |

**Retour:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Alpha replace effect.
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public final IBiLevel createBiLevel(float threshold)
```


Crée l'effet BiLevel.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| threshold | float | Seuil. |

**Retour:**
[IBiLevel](../../com.aspose.slides/ibilevel) - BiLevel effect.
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public final IBlur createBlur(double radius, boolean grow)
```


Crée l'effet Blur.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| radius | double | Rayon. |
| grow | boolean | Croissance. |

**Retour:**
[IBlur](../../com.aspose.slides/iblur) - Blur effect.
### createColorChange() {#createColorChange--}
```
public final IColorChange createColorChange()
```


Crée l'effet Color change.

**Retour:**
[IColorChange](../../com.aspose.slides/icolorchange) - Color change effect.
### createColorReplace() {#createColorReplace--}
```
public final IColorReplace createColorReplace()
```


Crée l'effet Color replace.

**Retour:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Color replace effect.
### createDuotone() {#createDuotone--}
```
public final IDuotone createDuotone()
```


Crée l'effet Duotone.

**Retour:**
[IDuotone](../../com.aspose.slides/iduotone) - Duotone effect.
### createFillOverlay() {#createFillOverlay--}
```
public final IFillOverlay createFillOverlay()
```


Crée l'effet Fill overlay.

**Retour:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Fill overlay effect.
### createGrayScale() {#createGrayScale--}
```
public final IGrayScale createGrayScale()
```


Crée l'effet Gray scale.

**Retour:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Renvoie l'effet Gray scale.
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public final IHSL createHSL(float hue, float saturation, float luminance)
```


Crée l'effet Hue Saturation Luminance.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| hue | float | Teinte. |
| saturation | float | Saturation. |
| luminance | float | Luminance. |

**Retour:**
[IHSL](../../com.aspose.slides/ihsl) - HSL effect.
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public final ILuminance createLuminance(float brightness, float contrast)
```


Crée l'effet Luminance.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brightness | float | Luminosité. |
| contrast | float | Contraste. |

**Retour:**
[ILuminance](../../com.aspose.slides/iluminance) - Luminance effect.
### createTint(float hue, float amount) {#createTint-float-float-}
```
public final ITint createTint(float hue, float amount)
```


Crée l'effet Tint.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| hue | float | Teinte. |
| amount | float | Quantité. |

**Retour:**
[ITint](../../com.aspose.slides/itint) - Tint effect.
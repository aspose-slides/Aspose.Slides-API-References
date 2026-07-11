---
title: ImageTransformOperationFactory
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Επιτρέπει τη δημιουργία λειτουργιών μετασχηματισμού εικόνας
type: docs
url: /el/com.aspose.slides/imagetransformoperationfactory/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory)
```
public class ImageTransformOperationFactory implements IImageTransformOperationFactory
```

Επιτρέπει τη δημιουργία λειτουργιών μετασχηματισμού εικόνας

--------------------

Για συμβατότητα με COM.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ImageTransformOperationFactory()](#ImageTransformOperationFactory--) |  |
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | Creates Alpha BiLevel effect. |
| [createAlphCeiling()](#createAlphCeiling--) | Creates Alpha Ceiling effect. |
| [createAlphaFloor()](#createAlphaFloor--) | Creates Alpha floor effect. |
| [createAlphaInverse()](#createAlphaInverse--) | Creates Alpha inverse effect. |
| [createAlphaModulate()](#createAlphaModulate--) | Creates Alpha modulate effect. |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | Creates Alpha modulate fixed effect. |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | Creates Alpha replace effect. |
| [createBiLevel(float threshold)](#createBiLevel-float-) | Creates BiLevel effect. |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | Creates Blur effect. |
| [createColorChange()](#createColorChange--) | Creates Color change effect. |
| [createColorReplace()](#createColorReplace--) | Creates Color replace effect. |
| [createDuotone()](#createDuotone--) | Creates Duotone effect. |
| [createFillOverlay()](#createFillOverlay--) | Creates Fill overlay effect. |
| [createGrayScale()](#createGrayScale--) | Creates Gray scale effect. |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | Creates Hue Saturation Luminance effect. |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | Createtes Luminance effect. |
| [createTint(float hue, float amount)](#createTint-float-float-) | Creates Tint effect. |
### ImageTransformOperationFactory() {#ImageTransformOperationFactory--}
```
public ImageTransformOperationFactory()
```


### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public final IAlphaBiLevel createAlphaBiLevel(float threshold)
```


Δημιουργεί εφέ Alpha BiLevel.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| threshold | float | Κατώφλι. |

**Επιστρέφει:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Alpha BiLevel εφέ.
### createAlphCeiling() {#createAlphCeiling--}
```
public final IAlphaCeiling createAlphCeiling()
```


Δημιουργεί εφέ Alpha Ceiling.

**Επιστρέφει:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Alpha Ceiling εφέ.
### createAlphaFloor() {#createAlphaFloor--}
```
public final IAlphaFloor createAlphaFloor()
```


Δημιουργεί εφέ Alpha floor.

**Επιστρέφει:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Alpha floor εφέ.
### createAlphaInverse() {#createAlphaInverse--}
```
public final IAlphaInverse createAlphaInverse()
```


Δημιουργεί εφέ Alpha inverse.

**Επιστρέφει:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Alpha inverst εφέ.
### createAlphaModulate() {#createAlphaModulate--}
```
public final IAlphaModulate createAlphaModulate()
```


Δημιουργεί εφέ Alpha modulate.

**Επιστρέφει:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Alpha modulate εφέ.
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public final IAlphaModulateFixed createAlphaModulateFixed(float amount)
```


Δημιουργεί εφέ Alpha modulate fixed.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| amount | float | Ποσό. |

**Επιστρέφει:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Alpha modulate fixed εφέ.
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public final IAlphaReplace createAlphaReplace(float alpha)
```


Δημιουργεί εφέ Alpha replace.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| alpha | float | Alpha |

**Επιστρέφει:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Alpha replace εφέ.
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public final IBiLevel createBiLevel(float threshold)
```


Δημιουργεί εφέ BiLevel.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| threshold | float | Κατώφλι. |

**Επιστρέφει:**
[IBiLevel](../../com.aspose.slides/ibilevel) - BiLevel εφέ.
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public final IBlur createBlur(double radius, boolean grow)
```


Δημιουργεί εφέ Blur.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| radius | double | Ακτίνα. |
| grow | boolean | Αύξηση. |

**Επιστρέφει:**
[IBlur](../../com.aspose.slides/iblur) - Blur εφέ.
### createColorChange() {#createColorChange--}
```
public final IColorChange createColorChange()
```


Δημιουργεί εφέ Color change.

**Επιστρέφει:**
[IColorChange](../../com.aspose.slides/icolorchange) - Color change εφέ.
### createColorReplace() {#createColorReplace--}
```
public final IColorReplace createColorReplace()
```


Δημιουργεί εφέ Color replace.

**Επιστρέφει:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Color replace εφέ.
### createDuotone() {#createDuotone--}
```
public final IDuotone createDuotone()
```


Δημιουργεί εφέ Duotone.

**Επιστρέφει:**
[IDuotone](../../com.aspose.slides/iduotone) - Duotone εφέ.
### createFillOverlay() {#createFillOverlay--}
```
public final IFillOverlay createFillOverlay()
```


Δημιουργεί εφέ Fill overlay.

**Επιστρέφει:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Fill overlay εφέ.
### createGrayScale() {#createGrayScale--}
```
public final IGrayScale createGrayScale()
```


Δημιουργεί εφέ Gray scale.

**Επιστρέφει:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Returns gray scale εφέ.
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public final IHSL createHSL(float hue, float saturation, float luminance)
```


Δημιουργεί εφέ Hue Saturation Luminance.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| hue | float | Hue. |
| saturation | float | Saturation. |
| luminance | float | Luminance. |

**Επιστρέφει:**
[IHSL](../../com.aspose.slides/ihsl) - HSL εφέ.
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public final ILuminance createLuminance(float brightness, float contrast)
```


Δημιουργεί εφέ Luminance.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| brightness | float | Brightness. |
| contrast | float | Contrast. |

**Επιστρέφει:**
[ILuminance](../../com.aspose.slides/iluminance) - Luminance εφέ.
### createTint(float hue, float amount) {#createTint-float-float-}
```
public final ITint createTint(float hue, float amount)
```


Δημιουργεί εφέ Tint.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| hue | float | Hue. |
| amount | float | Ποσό. |

**Επιστρέφει:**
[ITint](../../com.aspose.slides/itint) - Tint εφέ.
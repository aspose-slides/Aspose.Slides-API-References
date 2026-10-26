---
title: IImageTransformOperationFactory
second_title: Aspose.Slides for Java API Reference
description: Επιτρέπει τη δημιουργία παραδειγμάτων εφέ εικόνας
type: docs
url: /el/com.aspose.slides/iimagetransformoperationfactory/
---```
public interface IImageTransformOperationFactory
```

Επιτρέπει τη δημιουργία παραδειγμάτων εφέ εικόνας

--------------------

Για COM interface.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | Δημιουργεί το εφέ Alpha BiLevel. |
| [createAlphCeiling()](#createAlphCeiling--) | Δημιουργεί το εφέ Alpha Ceiling. |
| [createAlphaFloor()](#createAlphaFloor--) | Δημιουργεί το εφέ Alpha floor. |
| [createAlphaInverse()](#createAlphaInverse--) | Δημιουργεί το εφέ Alpha inverse. |
| [createAlphaModulate()](#createAlphaModulate--) | Δημιουργεί το εφέ Alpha modulate. |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | Δημιουργεί το εφέ Alpha modulate fixed. |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | Δημιουργεί το εφέ Alpha replace. |
| [createBiLevel(float threshold)](#createBiLevel-float-) | Δημιουργεί το εφέ BiLevel. |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | Δημιουργεί το εφέ Blur. |
| [createColorChange()](#createColorChange--) | Δημιουργεί το εφέ Color change. |
| [createColorReplace()](#createColorReplace--) | Δημιουργεί το εφέ Color replace. |
| [createDuotone()](#createDuotone--) | Δημιουργεί το εφέ Duotone. |
| [createFillOverlay()](#createFillOverlay--) | Δημιουργεί το εφέ Fill overlay. |
| [createGrayScale()](#createGrayScale--) | Δημιουργεί το εφέ Gray scale. |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | Δημιουργεί το εφέ Hue Saturation Luminance. |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | Δημιουργεί το εφέ Luminance. |
| [createTint(float hue, float amount)](#createTint-float-float-) | Δημιουργεί το εφέ Tint. |
### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public abstract IAlphaBiLevel createAlphaBiLevel(float threshold)
```


Δημιουργεί το εφέ Alpha BiLevel.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| threshold | float | Κατώφλι. |

**Επιστρέφει:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Alpha BiLevel εφέ.
### createAlphCeiling() {#createAlphCeiling--}
```
public abstract IAlphaCeiling createAlphCeiling()
```


Δημιουργεί το εφέ Alpha Ceiling.

**Επιστρέφει:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Alpha Ceiling εφέ.
### createAlphaFloor() {#createAlphaFloor--}
```
public abstract IAlphaFloor createAlphaFloor()
```


Δημιουργεί το εφέ Alpha floor.

**Επιστρέφει:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Alpha floor εφέ.
### createAlphaInverse() {#createAlphaInverse--}
```
public abstract IAlphaInverse createAlphaInverse()
```


Δημιουργεί το εφέ Alpha inverse.

**Επιστρέφει:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Alpha inverst εφέ.
### createAlphaModulate() {#createAlphaModulate--}
```
public abstract IAlphaModulate createAlphaModulate()
```


Δημιουργεί το εφέ Alpha modulate.

**Επιστρέφει:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Alpha modulate εφέ.
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public abstract IAlphaModulateFixed createAlphaModulateFixed(float amount)
```


Δημιουργεί το εφέ Alpha modulate fixed.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| amount | float | Ποσό. |

**Επιστρέφει:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Alpha modulate fixed εφέ.
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public abstract IAlphaReplace createAlphaReplace(float alpha)
```


Δημιουργεί το εφέ Alpha replace.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| alpha | float | Alpha |

**Επιστρέφει:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Alpha replace εφέ.
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public abstract IBiLevel createBiLevel(float threshold)
```


Δημιουργεί το εφέ BiLevel.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| threshold | float | Κατώφλι. |

**Επιστρέφει:**
[IBiLevel](../../com.aspose.slides/ibilevel) - BiLevel εφέ.
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public abstract IBlur createBlur(double radius, boolean grow)
```


Δημιουργεί το εφέ Blur.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| radius | double | Ακτίνα. |
| grow | boolean | Grow. |

**Επιστρέφει:**
[IBlur](../../com.aspose.slides/iblur) - Blur εφέ.
### createColorChange() {#createColorChange--}
```
public abstract IColorChange createColorChange()
```


Δημιουργεί το εφέ Color change.

**Επιστρέφει:**
[IColorChange](../../com.aspose.slides/icolorchange) - Color change εφέ.
### createColorReplace() {#createColorReplace--}
```
public abstract IColorReplace createColorReplace()
```


Δημιουργεί το εφέ Color replace.

**Επιστρέφει:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Color replace εφέ.
### createDuotone() {#createDuotone--}
```
public abstract IDuotone createDuotone()
```


Δημιουργεί το εφέ Duotone.

**Επιστρέφει:**
[IDuotone](../../com.aspose.slides/iduotone) - Duotone εφέ.
### createFillOverlay() {#createFillOverlay--}
```
public abstract IFillOverlay createFillOverlay()
```


Δημιουργεί το εφέ Fill overlay.

**Επιστρέφει:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Fill overlay εφέ.
### createGrayScale() {#createGrayScale--}
```
public abstract IGrayScale createGrayScale()
```


Δημιουργεί το εφέ Gray scale.

**Επιστρέφει:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Επιστροφή gray scale εφέ.
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public abstract IHSL createHSL(float hue, float saturation, float luminance)
```


Δημιουργεί το εφέ Hue Saturation Luminance.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hue | float | Hue. |
| saturation | float | Saturation. |
| luminance | float | Luminance. |

**Επιστρέφει:**
[IHSL](../../com.aspose.slides/ihsl) - HSL εφέ.
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public abstract ILuminance createLuminance(float brightness, float contrast)
```


Δημιουργεί το εφέ Luminance.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brightness | float | Brightness. |
| contrast | float | Contrast. |

**Επιστρέφει:**
[ILuminance](../../com.aspose.slides/iluminance) - Luminance εφέ.
### createTint(float hue, float amount) {#createTint-float-float-}
```
public abstract ITint createTint(float hue, float amount)
```


Δημιουργεί το εφέ Tint.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hue | float | Hue. |
| amount | float | Amount. |

**Επιστρέφει:**
[ITint](../../com.aspose.slides/itint) - Tint εφέ.
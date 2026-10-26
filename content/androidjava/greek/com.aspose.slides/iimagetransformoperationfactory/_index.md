---
title: IImageTransformOperationFactory
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Επιτρέπει τη δημιουργία αντικειμένων εφέ εικόνας
type: docs
url: /el/com.aspose.slides/iimagetransformoperationfactory/
---```
public interface IImageTransformOperationFactory
```

Επιτρέπει τη δημιουργία αντικειμένων εφέ εικόνας

--------------------

Για διεπαφή COM.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | Δημιουργεί εφέ Alpha BiLevel. |
| [createAlphCeiling()](#createAlphCeiling--) | Δημιουργεί εφέ Alpha Ceiling. |
| [createAlphaFloor()](#createAlphaFloor--) | Δημιουργεί εφέ Alpha floor. |
| [createAlphaInverse()](#createAlphaInverse--) | Δημιουργεί εφέ Alpha inverse. |
| [createAlphaModulate()](#createAlphaModulate--) | Δημιουργεί εφέ Alpha modulate. |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | Δημιουργεί εφέ Alpha modulate fixed. |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | Δημιουργεί εφέ Alpha replace. |
| [createBiLevel(float threshold)](#createBiLevel-float-) | Δημιουργεί εφέ BiLevel. |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | Δημιουργεί εφέ Blur. |
| [createColorChange()](#createColorChange--) | Δημιουργεί εφέ Color change. |
| [createColorReplace()](#createColorReplace--) | Δημιουργεί εφέ Color replace. |
| [createDuotone()](#createDuotone--) | Δημιουργεί εφέ Duotone. |
| [createFillOverlay()](#createFillOverlay--) | Δημιουργεί εφέ Fill overlay. |
| [createGrayScale()](#createGrayScale--) | Δημιουργεί εφέ Gray scale. |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | Δημιουργεί εφέ Hue Saturation Luminance. |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | Δημιουργεί εφέ Luminance. |
| [createTint(float hue, float amount)](#createTint-float-float-) | Δημιουργεί εφέ Tint. |
### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public abstract IAlphaBiLevel createAlphaBiLevel(float threshold)
```

Δημιουργεί εφέ Alpha BiLevel.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| threshold | float | Κατώφλι. |

**Επιστρέφει:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Εφέ Alpha BiLevel.
### createAlphCeiling() {#createAlphCeiling--}
```
public abstract IAlphaCeiling createAlphCeiling()
```

Δημιουργεί εφέ Alpha Ceiling.

**Επιστρέφει:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Εφέ Alpha Ceiling.
### createAlphaFloor() {#createAlphaFloor--}
```
public abstract IAlphaFloor createAlphaFloor()
```

Δημιουργεί εφέ Alpha floor.

**Επιστρέφει:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Εφέ Alpha floor.
### createAlphaInverse() {#createAlphaInverse--}
```
public abstract IAlphaInverse createAlphaInverse()
```

Δημιουργεί εφέ Alpha inverse.

**Επιστρέφει:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Εφέ Alpha inverst.
### createAlphaModulate() {#createAlphaModulate--}
```
public abstract IAlphaModulate createAlphaModulate()
```

Δημιουργεί εφέ Alpha modulate.

**Επιστρέφει:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Εφέ Alpha modulate.
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public abstract IAlphaModulateFixed createAlphaModulateFixed(float amount)
```

Δημιουργεί εφέ Alpha modulate fixed.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| amount | float | Ποσό. |

**Επιστρέφει:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Εφέ Alpha modulate fixed.
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public abstract IAlphaReplace createAlphaReplace(float alpha)
```

Δημιουργεί εφέ Alpha replace.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| alpha | float | Alpha |

**Επιστρέφει:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Εφέ Alpha replace.
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public abstract IBiLevel createBiLevel(float threshold)
```

Δημιουργεί εφέ BiLevel.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| threshold | float | Κατώφλι. |

**Επιστρέφει:**
[IBiLevel](../../com.aspose.slides/ibilevel) - Εφέ BiLevel.
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public abstract IBlur createBlur(double radius, boolean grow)
```

Δημιουργεί εφέ Blur.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| radius | double | Ακτίνα. |
| grow | boolean | Grow. |

**Επιστρέφει:**
[IBlur](../../com.aspose.slides/iblur) - Εφέ Blur.
### createColorChange() {#createColorChange--}
```
public abstract IColorChange createColorChange()
```

Δημιουργεί εφέ Color change.

**Επιστρέφει:**
[IColorChange](../../com.aspose.slides/icolorchange) - Εφέ Color change.
### createColorReplace() {#createColorReplace--}
```
public abstract IColorReplace createColorReplace()
```

Δημιουργεί εφέ Color replace.

**Επιστρέφει:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Εφέ Color replace.
### createDuotone() {#createDuotone--}
```
public abstract IDuotone createDuotone()
```

Δημιουργεί εφέ Duotone.

**Επιστρέφει:**
[IDuotone](../../com.aspose.slides/iduotone) - Εφέ Duotone.
### createFillOverlay() {#createFillOverlay--}
```
public abstract IFillOverlay createFillOverlay()
```

Δημιουργεί εφέ Fill overlay.

**Επιστρέφει:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Εφέ Fill overlay.
### createGrayScale() {#createGrayScale--}
```
public abstract IGrayScale createGrayScale()
```

Δημιουργεί εφέ Gray scale.

**Επιστρέφει:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Εφέ Gray scale.
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public abstract IHSL createHSL(float hue, float saturation, float luminance)
```

Δημιουργεί εφέ Hue Saturation Luminance.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hue | float | Hue. |
| saturation | float | Saturation. |
| luminance | float | Luminance. |

**Επιστρέφει:**
[IHSL](../../com.aspose.slides/ihsl) - Εφέ HSL.
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public abstract ILuminance createLuminance(float brightness, float contrast)
```

Δημιουργεί εφέ Luminance.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brightness | float | Brightness. |
| contrast | float | Contrast. |

**Επιστρέφει:**
[ILuminance](../../com.aspose.slides/iluminance) - Εφέ Luminance.
### createTint(float hue, float amount) {#createTint-float-float-}
```
public abstract ITint createTint(float hue, float amount)
```

Δημιουργεί εφέ Tint.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hue | float | Hue. |
| amount | float | Amount. |

**Επιστρέφει:**
[ITint](../../com.aspose.slides/itint) - Εφέ Tint.
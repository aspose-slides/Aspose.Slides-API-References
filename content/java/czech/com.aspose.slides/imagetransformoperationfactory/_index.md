---
title: ImageTransformOperationFactory
second_title: Aspose.Slides pro Java – referenční dokumentace API
description: Umožňuje vytvářet operace transformace obrazu
type: docs
url: /cs/com.aspose.slides/imagetransformoperationfactory/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory)
```
public class ImageTransformOperationFactory implements IImageTransformOperationFactory
```

Umožňuje vytvářet operace transformace obrazu

--------------------

Pro kompatibilitu s COM.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [ImageTransformOperationFactory()](#ImageTransformOperationFactory--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | Vytváří efekt Alpha BiLevel. |
| [createAlphCeiling()](#createAlphCeiling--) | Vytváří efekt Alpha Ceiling. |
| [createAlphaFloor()](#createAlphaFloor--) | Vytváří efekt Alpha floor. |
| [createAlphaInverse()](#createAlphaInverse--) | Vytváří efekt Alpha inverse. |
| [createAlphaModulate()](#createAlphaModulate--) | Vytváří efekt Alpha modulate. |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | Vytváří efekt Alpha modulate fixed. |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | Vytváří efekt Alpha replace. |
| [createBiLevel(float threshold)](#createBiLevel-float-) | Vytváří efekt BiLevel. |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | Vytváří efekt Blur. |
| [createColorChange()](#createColorChange--) | Vytváří efekt Color change. |
| [createColorReplace()](#createColorReplace--) | Vytváří efekt Color replace. |
| [createDuotone()](#createDuotone--) | Vytváří efekt Duotone. |
| [createFillOverlay()](#createFillOverlay--) | Vytváří efekt Fill overlay. |
| [createGrayScale()](#createGrayScale--) | Vytváří efekt Gray scale. |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | Vytváří efekt Hue Saturation Luminance. |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | Vytváří efekt Luminance. |
| [createTint(float hue, float amount)](#createTint-float-float-) | Vytváří efekt Tint. |
### ImageTransformOperationFactory() {#ImageTransformOperationFactory--}
```
public ImageTransformOperationFactory()
```

### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public final IAlphaBiLevel createAlphaBiLevel(float threshold)
```

Vytváří efekt Alpha BiLevel.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| threshold | float | Prahová hodnota. |

**Vrací:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - efekt Alpha BiLevel.
### createAlphCeiling() {#createAlphCeiling--}
```
public final IAlphaCeiling createAlphCeiling()
```

Vytváří efekt Alpha Ceiling.

**Vrací:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - efekt Alpha Ceiling.
### createAlphaFloor() {#createAlphaFloor--}
```
public final IAlphaFloor createAlphaFloor()
```

Vytváří efekt Alpha floor.

**Vrací:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - efekt Alpha floor.
### createAlphaInverse() {#createAlphaInverse--}
```
public final IAlphaInverse createAlphaInverse()
```

Vytváří efekt Alpha inverse.

**Vrací:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - efekt Alpha inverse.
### createAlphaModulate() {#createAlphaModulate--}
```
public final IAlphaModulate createAlphaModulate()
```

Vytváří efekt Alpha modulate.

**Vrací:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - efekt Alpha modulate.
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public final IAlphaModulateFixed createAlphaModulateFixed(float amount)
```

Vytváří efekt Alpha modulate fixed.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| amount | float | Množství. |

**Vrací:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - efekt Alpha modulate fixed.
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public final IAlphaReplace createAlphaReplace(float alpha)
```

Vytváří efekt Alpha replace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| alpha | float | Alpha |

**Vrací:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - efekt Alpha replace.
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public final IBiLevel createBiLevel(float threshold)
```

Vytváří efekt BiLevel.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| threshold | float | Prahová hodnota. |

**Vrací:**
[IBiLevel](../../com.aspose.slides/ibilevel) - efekt BiLevel.
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public final IBlur createBlur(double radius, boolean grow)
```

Vytváří efekt Blur.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| radius | double | Poloměr. |
| grow | boolean | Rozšířit. |

**Vrací:**
[IBlur](../../com.aspose.slides/iblur) - efekt Blur.
### createColorChange() {#createColorChange--}
```
public final IColorChange createColorChange()
```

Vytváří efekt Color change.

**Vrací:**
[IColorChange](../../com.aspose.slides/icolorchange) - efekt Color change.
### createColorReplace() {#createColorReplace--}
```
public final IColorReplace createColorReplace()
```

Vytváří efekt Color replace.

**Vrací:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - efekt Color replace.
### createDuotone() {#createDuotone--}
```
public final IDuotone createDuotone()
```

Vytváří efekt Duotone.

**Vrací:**
[IDuotone](../../com.aspose.slides/iduotone) - efekt Duotone.
### createFillOverlay() {#createFillOverlay--}
```
public final IFillOverlay createFillOverlay()
```

Vytváří efekt Fill overlay.

**Vrací:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - efekt Fill overlay.
### createGrayScale() {#createGrayScale--}
```
public final IGrayScale createGrayScale()
```

Vytváří efekt Gray scale.

**Vrací:**
[IGrayScale](../../com.aspose.slides/igrayscale) - efekt Gray scale.
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public final IHSL createHSL(float hue, float saturation, float luminance)
```

Vytváří efekt Hue Saturation Luminance.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| hue | float | Odstín. |
| saturation | float | Sytost. |
| luminance | float | Luminance. |

**Vrací:**
[IHSL](../../com.aspose.slides/ihsl) - efekt HSL.
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public final ILuminance createLuminance(float brightness, float contrast)
```

Vytváří efekt Luminance.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| brightness | float | Jas. |
| contrast | float | Kontrast. |

**Vrací:**
[ILuminance](../../com.aspose.slides/iluminance) - efekt Luminance.
### createTint(float hue, float amount) {#createTint-float-float-}
```
public final ITint createTint(float hue, float amount)
```

Vytváří efekt Tint.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| hue | float | Odstín. |
| amount | float | Množství. |

**Vrací:**
[ITint](../../com.aspose.slides/itint) - efekt Tint.
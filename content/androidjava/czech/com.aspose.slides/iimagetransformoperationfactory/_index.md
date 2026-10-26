---
title: IImageTransformOperationFactory
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Umožňuje vytvářet instance efektů obrazu
type: docs
url: /cs/com.aspose.slides/iimagetransformoperationfactory/
---```
public interface IImageTransformOperationFactory
```

Umožňuje vytvářet instance efektů obrazu

--------------------

Pro rozhraní COM.
## Metody

| Metoda | Popis |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | Vytváří Alpha BiLevel effect. |
| [createAlphCeiling()](#createAlphCeiling--) | Vytváří Alpha Ceiling effect. |
| [createAlphaFloor()](#createAlphaFloor--) | Vytváří Alpha floor effect. |
| [createAlphaInverse()](#createAlphaInverse--) | Vytváří Alpha inverse effect. |
| [createAlphaModulate()](#createAlphaModulate--) | Vytváří Alpha modulate effect. |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | Vytváří Alpha modulate fixed effect. |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | Vytváří Alpha replace effect. |
| [createBiLevel(float threshold)](#createBiLevel-float-) | Vytváří BiLevel effect. |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | Vytváří Blur effect. |
| [createColorChange()](#createColorChange--) | Vytváří Color change effect. |
| [createColorReplace()](#createColorReplace--) | Vytváří Color replace effect. |
| [createDuotone()](#createDuotone--) | Vytváří Duotone effect. |
| [createFillOverlay()](#createFillOverlay--) | Vytváří Fill overlay effect. |
| [createGrayScale()](#createGrayScale--) | Vytváří Gray scale effect. |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | Vytváří Hue Saturation Luminance effect. |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | Vytváří Luminance effect. |
| [createTint(float hue, float amount)](#createTint-float-float-) | Vytváří Tint effect. |
### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public abstract IAlphaBiLevel createAlphaBiLevel(float threshold)
```

Vytváří Alpha BiLevel effect.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| threshold | float | Prahová hodnota. |

**Návratová hodnota:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Alpha BiLevel effect.
### createAlphCeiling() {#createAlphCeiling--}
```
public abstract IAlphaCeiling createAlphCeiling()
```

Vytváří Alpha Ceiling effect.

**Návratová hodnota:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Alpha Ceiling effect.
### createAlphaFloor() {#createAlphaFloor--}
```
public abstract IAlphaFloor createAlphaFloor()
```

Vytváří Alpha floor effect.

**Návratová hodnota:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Alpha floor effect.
### createAlphaInverse() {#createAlphaInverse--}
```
public abstract IAlphaInverse createAlphaInverse()
```

Vytváří Alpha inverse effect.

**Návratová hodnota:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Alpha inverst effect.
### createAlphaModulate() {#createAlphaModulate--}
```
public abstract IAlphaModulate createAlphaModulate()
```

Vytváří Alpha modulate effect.

**Návratová hodnota:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Alpha modulate effect.
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public abstract IAlphaModulateFixed createAlphaModulateFixed(float amount)
```

Vytváří Alpha modulate fixed effect.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| amount | float | Amount. |

**Návratová hodnota:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Alpha modulate fixed effect.
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public abstract IAlphaReplace createAlphaReplace(float alpha)
```

Vytváří Alpha replace effect.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| alpha | float | Alpha |

**Návratová hodnota:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Alpha replace effect.
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public abstract IBiLevel createBiLevel(float threshold)
```

Vytváří BiLevel effect.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| threshold | float | Prahová hodnota. |

**Návratová hodnota:**
[IBiLevel](../../com.aspose.slides/ibilevel) - BiLevel effect.
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public abstract IBlur createBlur(double radius, boolean grow)
```

Vytváří Blur effect.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| radius | double | Radius. |
| grow | boolean | Grow. |

**Návratová hodnota:**
[IBlur](../../com.aspose.slides/iblur) - Blur effect.
### createColorChange() {#createColorChange--}
```
public abstract IColorChange createColorChange()
```

Vytváří Color change effect.

**Návratová hodnota:**
[IColorChange](../../com.aspose.slides/icolorchange) - Color change effect.
### createColorReplace() {#createColorReplace--}
```
public abstract IColorReplace createColorReplace()
```

Vytváří Color replace effect.

**Návratová hodnota:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Color replace effect.
### createDuotone() {#createDuotone--}
```
public abstract IDuotone createDuotone()
```

Vytváří Duotone effect.

**Návratová hodnota:**
[IDuotone](../../com.aspose.slides/iduotone) - Duotone effect.
### createFillOverlay() {#createFillOverlay--}
```
public abstract IFillOverlay createFillOverlay()
```

Vytváří Fill overlay effect.

**Návratová hodnota:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Fill overlay effect.
### createGrayScale() {#createGrayScale--}
```
public abstract IGrayScale createGrayScale()
```

Vytváří Gray scale effect.

**Návratová hodnota:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Vrací gray scale effect.
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public abstract IHSL createHSL(float hue, float saturation, float luminance)
```

Vytváří Hue Saturation Luminance effect.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| hue | float | Hue. |
| saturation | float | Saturation. |
| luminance | float | Luminance. |

**Návratová hodnota:**
[IHSL](../../com.aspose.slides/ihsl) - HSL effect.
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public abstract ILuminance createLuminance(float brightness, float contrast)
```

Vytváří Luminance effect.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| brightness | float | Brightness. |
| contrast | float | Contrast. |

**Návratová hodnota:**
[ILuminance](../../com.aspose.slides/iluminance) - Luminance effect.
### createTint(float hue, float amount) {#createTint-float-float-}
```
public abstract ITint createTint(float hue, float amount)
```

Vytváří Tint effect.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| hue | float | Hue. |
| amount | float | Amount. |

**Návratová hodnota:**
[ITint](../../com.aspose.slides/itint) - Tint effect.
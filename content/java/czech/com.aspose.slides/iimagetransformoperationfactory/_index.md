---
title: IImageTransformOperationFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create image effects instances
type: docs
url: /cs/com.aspose.slides/iimagetransformoperationfactory/
---```
public interface IImageTransformOperationFactory
```

Umožňuje vytvářet instance efektů obrázků

--------------------

Pro rozhraní COM.
## Metody

| Metoda | Popis |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | Vytvoří efekt Alpha BiLevel. |
| [createAlphCeiling()](#createAlphCeiling--) | Vytvoří efekt Alpha Ceiling. |
| [createAlphaFloor()](#createAlphaFloor--) | Vytvoří efekt Alpha floor. |
| [createAlphaInverse()](#createAlphaInverse--) | Vytvoří efekt Alpha inverse. |
| [createAlphaModulate()](#createAlphaModulate--) | Vytvoří efekt Alpha modulate. |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | Vytvoří efekt Alpha modulate fixed. |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | Vytvoří efekt Alpha replace. |
| [createBiLevel(float threshold)](#createBiLevel-float-) | Vytvoří efekt BiLevel. |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | Vytvoří efekt Blur. |
| [createColorChange()](#createColorChange--) | Vytvoří efekt Color change. |
| [createColorReplace()](#createColorReplace--) | Vytvoří efekt Color replace. |
| [createDuotone()](#createDuotone--) | Vytvoří efekt Duotone. |
| [createFillOverlay()](#createFillOverlay--) | Vytvoří efekt Fill overlay. |
| [createGrayScale()](#createGrayScale--) | Vytvoří efekt Gray scale. |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | Vytvoří efekt Hue Saturation Luminance. |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | Vytvoří efekt Luminance. |
| [createTint(float hue, float amount)](#createTint-float-float-) | Vytvoří efekt Tint. |
### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public abstract IAlphaBiLevel createAlphaBiLevel(float threshold)
```

Vytvoří efekt Alpha BiLevel.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| threshold | float | Threshold. |

**Vrací:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Alpha BiLevel efekt.
### createAlphCeiling() {#createAlphCeiling--}
```
public abstract IAlphaCeiling createAlphCeiling()
```

Vytvoří efekt Alpha Ceiling.

**Vrací:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Alpha Ceiling efekt.
### createAlphaFloor() {#createAlphaFloor--}
```
public abstract IAlphaFloor createAlphaFloor()
```

Vytvoří efekt Alpha floor.

**Vrací:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Alpha floor efekt.
### createAlphaInverse() {#createAlphaInverse--}
```
public abstract IAlphaInverse createAlphaInverse()
```

Vytvoří efekt Alpha inverse.

**Vrací:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Alpha inverse efekt.
### createAlphaModulate() {#createAlphaModulate--}
```
public abstract IAlphaModulate createAlphaModulate()
```

Vytvoří efekt Alpha modulate.

**Vrací:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Alpha modulate efekt.
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public abstract IAlphaModulateFixed createAlphaModulateFixed(float amount)
```

Vytvoří efekt Alpha modulate fixed.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| amount | float | Amount. |

**Vrací:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Alpha modulate fixed efekt.
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public abstract IAlphaReplace createAlphaReplace(float alpha)
```

Vytvoří efekt Alpha replace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| alpha | float | Alpha |

**Vrací:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Alpha replace efekt.
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public abstract IBiLevel createBiLevel(float threshold)
```

Vytvoří efekt BiLevel.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| threshold | float | Threshold. |

**Vrací:**
[IBiLevel](../../com.aspose.slides/ibilevel) - BiLevel efekt.
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public abstract IBlur createBlur(double radius, boolean grow)
```

Vytvoří efekt Blur.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| radius | double | Radius. |
| grow | boolean | Grow. |

**Vrací:**
[IBlur](../../com.aspose.slides/iblur) - Blur efekt.
### createColorChange() {#createColorChange--}
```
public abstract IColorChange createColorChange()
```

Vytvoří efekt Color change.

**Vrací:**
[IColorChange](../../com.aspose.slides/icolorchange) - Color change efekt.
### createColorReplace() {#createColorReplace--}
```
public abstract IColorReplace createColorReplace()
```

Vytvoří efekt Color replace.

**Vrací:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Color replace efekt.
### createDuotone() {#createDuotone--}
```
public abstract IDuotone createDuotone()
```

Vytvoří efekt Duotone.

**Vrací:**
[IDuotone](../../com.aspose.slides/iduotone) - Duotone efekt.
### createFillOverlay() {#createFillOverlay--}
```
public abstract IFillOverlay createFillOverlay()
```

Vytvoří efekt Fill overlay.

**Vrací:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Fill overlay efekt.
### createGrayScale() {#createGrayScale--}
```
public abstract IGrayScale createGrayScale()
```

Vytvoří efekt Gray scale.

**Vrací:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Gray scale efekt.
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public abstract IHSL createHSL(float hue, float saturation, float luminance)
```

Vytvoří efekt Hue Saturation Luminance.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| hue | float | Hue. |
| saturation | float | Saturation. |
| luminance | float | Luminance. |

**Vrací:**
[IHSL](../../com.aspose.slides/ihsl) - HSL efekt.
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public abstract ILuminance createLuminance(float brightness, float contrast)
```

Vytvoří efekt Luminance.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| brightness | float | Brightness. |
| contrast | float | Contrast. |

**Vrací:**
[ILuminance](../../com.aspose.slides/iluminance) - Luminance efekt.
### createTint(float hue, float amount) {#createTint-float-float-}
```
public abstract ITint createTint(float hue, float amount)
```

Vytvoří efekt Tint.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| hue | float | Hue. |
| amount | float | Amount. |

**Vrací:**
[ITint](../../com.aspose.slides/itint) - Tint efekt.
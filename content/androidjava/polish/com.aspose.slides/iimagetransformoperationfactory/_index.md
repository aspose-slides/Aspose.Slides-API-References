---
title: IImageTransformOperationFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create image effects instances
type: docs
url: /pl/com.aspose.slides/iimagetransformoperationfactory/
---```
public interface IImageTransformOperationFactory
```

Umożliwia tworzenie instancji efektów obrazu

--------------------

Dla interfejsu COM.
## Metody

| Metoda | Opis |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | Tworzy efekt Alpha BiLevel. |
| [createAlphCeiling()](#createAlphCeiling--) | Tworzy efekt Alpha Ceiling. |
| [createAlphaFloor()](#createAlphaFloor--) | Tworzy efekt Alpha floor. |
| [createAlphaInverse()](#createAlphaInverse--) | Tworzy efekt Alpha inverse. |
| [createAlphaModulate()](#createAlphaModulate--) | Tworzy efekt Alpha modulate. |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | Tworzy efekt Alpha modulate fixed. |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | Tworzy efekt Alpha replace. |
| [createBiLevel(float threshold)](#createBiLevel-float-) | Tworzy efekt BiLevel. |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | Tworzy efekt Blur. |
| [createColorChange()](#createColorChange--) | Tworzy efekt Color change. |
| [createColorReplace()](#createColorReplace--) | Tworzy efekt Color replace. |
| [createDuotone()](#createDuotone--) | Tworzy efekt Duotone. |
| [createFillOverlay()](#createFillOverlay--) | Tworzy efekt Fill overlay. |
| [createGrayScale()](#createGrayScale--) | Tworzy efekt Gray scale. |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | Tworzy efekt Hue Saturation Luminance. |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | Tworzy efekt Luminance. |
| [createTint(float hue, float amount)](#createTint-float-float-) | Tworzy efekt Tint. |
### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public abstract IAlphaBiLevel createAlphaBiLevel(float threshold)
```


Tworzy efekt Alpha BiLevel.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| threshold | float | Próg. |

**Zwraca:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - efekt Alpha BiLevel.
### createAlphCeiling() {#createAlphCeiling--}
```
public abstract IAlphaCeiling createAlphCeiling()
```


Tworzy efekt Alpha Ceiling.

**Zwraca:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - efekt Alpha Ceiling.
### createAlphaFloor() {#createAlphaFloor--}
```
public abstract IAlphaFloor createAlphaFloor()
```


Tworzy efekt Alpha floor.

**Zwraca:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - efekt Alpha floor.
### createAlphaInverse() {#createAlphaInverse--}
```
public abstract IAlphaInverse createAlphaInverse()
```


Tworzy efekt Alpha inverse.

**Zwraca:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - efekt Alpha inverst.
### createAlphaModulate() {#createAlphaModulate--}
```
public abstract IAlphaModulate createAlphaModulate()
```


Tworzy efekt Alpha modulate.

**Zwraca:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - efekt Alpha modulate.
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public abstract IAlphaModulateFixed createAlphaModulateFixed(float amount)
```


Tworzy efekt Alpha modulate fixed.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| amount | float | Ilość. |

**Zwraca:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - efekt Alpha modulate fixed.
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public abstract IAlphaReplace createAlphaReplace(float alpha)
```


Tworzy efekt Alpha replace.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| alpha | float | Alpha |

**Zwraca:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - efekt Alpha replace.
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public abstract IBiLevel createBiLevel(float threshold)
```


Tworzy efekt BiLevel.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| threshold | float | Próg. |

**Zwraca:**
[IBiLevel](../../com.aspose.slides/ibilevel) - efekt BiLevel.
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public abstract IBlur createBlur(double radius, boolean grow)
```


Tworzy efekt Blur.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| radius | double | Promień. |
| grow | boolean | Rozszerzanie. |

**Zwraca:**
[IBlur](../../com.aspose.slides/iblur) - efekt Blur.
### createColorChange() {#createColorChange--}
```
public abstract IColorChange createColorChange()
```


Tworzy efekt Color change.

**Zwraca:**
[IColorChange](../../com.aspose.slides/icolorchange) - efekt Color change.
### createColorReplace() {#createColorReplace--}
```
public abstract IColorReplace createColorReplace()
```


Tworzy efekt Color replace.

**Zwraca:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - efekt Color replace.
### createDuotone() {#createDuotone--}
```
public abstract IDuotone createDuotone()
```


Tworzy efekt Duotone.

**Zwraca:**
[IDuotone](../../com.aspose.slides/iduotone) - efekt Duotone.
### createFillOverlay() {#createFillOverlay--}
```
public abstract IFillOverlay createFillOverlay()
```


Tworzy efekt Fill overlay.

**Zwraca:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - efekt Fill overlay.
### createGrayScale() {#createGrayScale--}
```
public abstract IGrayScale createGrayScale()
```


Tworzy efekt Gray scale.

**Zwraca:**
[IGrayScale](../../com.aspose.slides/igrayscale) - efekt Gray scale.
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public abstract IHSL createHSL(float hue, float saturation, float luminance)
```


Tworzy efekt Hue Saturation Luminance.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| hue | float | Odcień. |
| saturation | float | Nasycenie. |
| luminance | float | Jasność. |

**Zwraca:**
[IHSL](../../com.aspose.slides/ihsl) - efekt HSL.
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public abstract ILuminance createLuminance(float brightness, float contrast)
```


Tworzy efekt Luminance.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| brightness | float | Jasność. |
| contrast | float | Kontrast. |

**Zwraca:**
[ILuminance](../../com.aspose.slides/iluminance) - efekt Luminance.
### createTint(float hue, float amount) {#createTint-float-float-}
```
public abstract ITint createTint(float hue, float amount)
```


Tworzy efekt Tint.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| hue | float | Odcień. |
| amount | float | Ilość. |

**Zwraca:**
[ITint](../../com.aspose.slides/itint) - efekt Tint.
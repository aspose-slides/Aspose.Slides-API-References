---
title: IImageTransformOperationFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Tillåter att skapa instanser av bildeffekter
type: docs
url: /sv/com.aspose.slides/iimagetransformoperationfactory/
---```
public interface IImageTransformOperationFactory
```

Tillåter att skapa instanser av bildeffekter

--------------------

For COM interface.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | Skapar Alpha BiLevel-effekt. |
| [createAlphCeiling()](#createAlphCeiling--) | Skapar Alpha Ceiling-effekt. |
| [createAlphaFloor()](#createAlphaFloor--) | Skapar Alpha floor-effekt. |
| [createAlphaInverse()](#createAlphaInverse--) | Skapar Alpha inverse-effekt. |
| [createAlphaModulate()](#createAlphaModulate--) | Skapar Alpha modulate-effekt. |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | Skapar Alpha modulate fixed-effekt. |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | Skapar Alpha replace-effekt. |
| [createBiLevel(float threshold)](#createBiLevel-float-) | Skapar BiLevel-effekt. |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | Skapar Blur-effekt. |
| [createColorChange()](#createColorChange--) | Skapar Color change-effekt. |
| [createColorReplace()](#createColorReplace--) | Skapar Color replace-effekt. |
| [createDuotone()](#createDuotone--) | Skapar Duotone-effekt. |
| [createFillOverlay()](#createFillOverlay--) | Skapar Fill overlay-effekt. |
| [createGrayScale()](#createGrayScale--) | Skapar Gray scale-effekt. |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | Skapar Hue Saturation Luminance-effekt. |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | Skapar Luminance-effekt. |
| [createTint(float hue, float amount)](#createTint-float-float-) | Skapar Tint-effekt. |
### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public abstract IAlphaBiLevel createAlphaBiLevel(float threshold)
```


Skapar Alpha BiLevel-effekt.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| threshold | float | Tröskelvärde. |

**Returnerar:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Alpha BiLevel-effekt.
### createAlphCeiling() {#createAlphCeiling--}
```
public abstract IAlphaCeiling createAlphCeiling()
```


Skapar Alpha Ceiling-effekt.

**Returnerar:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Alpha Ceiling-effekt.
### createAlphaFloor() {#createAlphaFloor--}
```
public abstract IAlphaFloor createAlphaFloor()
```


Skapar Alpha floor-effekt.

**Returnerar:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Alpha floor-effekt.
### createAlphaInverse() {#createAlphaInverse--}
```
public abstract IAlphaInverse createAlphaInverse()
```


Skapar Alpha inverse-effekt.

**Returnerar:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Alpha inverst-effekt.
### createAlphaModulate() {#createAlphaModulate--}
```
public abstract IAlphaModulate createAlphaModulate()
```


Skapar Alpha modulate-effekt.

**Returnerar:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Alpha modulate-effekt.
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public abstract IAlphaModulateFixed createAlphaModulateFixed(float amount)
```


Skapar Alpha modulate fixed-effekt.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| amount | float | Mängd. |

**Returnerar:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Alpha modulate fixed-effekt.
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public abstract IAlphaReplace createAlphaReplace(float alpha)
```


Skapar Alpha replace-effekt.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| alpha | float | Alpha |

**Returnerar:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Alpha replace-effekt.
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public abstract IBiLevel createBiLevel(float threshold)
```


Skapar BiLevel-effekt.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| threshold | float | Tröskelvärde. |

**Returnerar:**
[IBiLevel](../../com.aspose.slides/ibilevel) - BiLevel-effekt.
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public abstract IBlur createBlur(double radius, boolean grow)
```


Skapar Blur-effekt.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| radius | double | Radie. |
| grow | boolean | Öka. |

**Returnerar:**
[IBlur](../../com.aspose.slides/iblur) - Blur-effekt.
### createColorChange() {#createColorChange--}
```
public abstract IColorChange createColorChange()
```


Skapar Color change-effekt.

**Returnerar:**
[IColorChange](../../com.aspose.slides/icolorchange) - Color change-effekt.
### createColorReplace() {#createColorReplace--}
```
public abstract IColorReplace createColorReplace()
```


Skapar Color replace-effekt.

**Returnerar:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Color replace-effekt.
### createDuotone() {#createDuotone--}
```
public abstract IDuotone createDuotone()
```


Skapar Duotone-effekt.

**Returnerar:**
[IDuotone](../../com.aspose.slides/iduotone) - Duotone-effekt.
### createFillOverlay() {#createFillOverlay--}
```
public abstract IFillOverlay createFillOverlay()
```


Skapar Fill overlay-effekt.

**Returnerar:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Fill overlay-effekt.
### createGrayScale() {#createGrayScale--}
```
public abstract IGrayScale createGrayScale()
```


Skapar Gray scale-effekt.

**Returnerar:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Returnerar gray scale-effekt.
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public abstract IHSL createHSL(float hue, float saturation, float luminance)
```


Skapar Hue Saturation Luminance-effekt.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| hue | float | Nyans. |
| saturation | float | Mättnad. |
| luminance | float | Luminans. |

**Returnerar:**
[IHSL](../../com.aspose.slides/ihsl) - HSL-effekt.
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public abstract ILuminance createLuminance(float brightness, float contrast)
```


Skapar Luminance-effekt.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| brightness | float | Ljusstyrka. |
| contrast | float | Kontrast. |

**Returnerar:**
[ILuminance](../../com.aspose.slides/iluminance) - Luminance-effekt.
### createTint(float hue, float amount) {#createTint-float-float-}
```
public abstract ITint createTint(float hue, float amount)
```


Skapar Tint-effekt.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| hue | float | Nyans. |
| amount | float | Mängd. |

**Returnerar:**
[ITint](../../com.aspose.slides/itint) - Tint-effekt.
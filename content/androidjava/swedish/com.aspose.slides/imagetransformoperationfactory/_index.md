---
title: ImageTransformOperationFactory
second_title: Aspose.Slides för Android via Java API-referens
description: Tillåter att skapa bildtransformeringsoperationer
type: docs
url: /sv/com.aspose.slides/imagetransformoperationfactory/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory)
```
public class ImageTransformOperationFactory implements IImageTransformOperationFactory
```

Gör det möjligt att skapa bildtransformeringsoperationer

--------------------

För COM-kompatibilitet.
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [ImageTransformOperationFactory()](#ImageTransformOperationFactory--) |  |
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
### ImageTransformOperationFactory() {#ImageTransformOperationFactory--}
```
public ImageTransformOperationFactory()
```

### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public final IAlphaBiLevel createAlphaBiLevel(float threshold)
```

Skapar Alpha BiLevel-effekt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threshold | float | Tröskel. |

**Returnerar:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Alpha BiLevel-effekt.
### createAlphCeiling() {#createAlphCeiling--}
```
public final IAlphaCeiling createAlphCeiling()
```

Skapar Alpha Ceiling-effekt.

**Returnerar:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Alpha Ceiling-effekt.
### createAlphaFloor() {#createAlphaFloor--}
```
public final IAlphaFloor createAlphaFloor()
```

Skapar Alpha floor-effekt.

**Returnerar:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Alpha floor-effekt.
### createAlphaInverse() {#createAlphaInverse--}
```
public final IAlphaInverse createAlphaInverse()
```

Skapar Alpha inverse-effekt.

**Returnerar:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Alpha inverse-effekt.
### createAlphaModulate() {#createAlphaModulate--}
```
public final IAlphaModulate createAlphaModulate()
```

Skapar Alpha modulate-effekt.

**Returnerar:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Alpha modulate-effekt.
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public final IAlphaModulateFixed createAlphaModulateFixed(float amount)
```

Skapar Alpha modulate fixed-effekt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| amount | float | Mängd. |

**Returnerar:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Alpha modulate fixed-effekt.
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public final IAlphaReplace createAlphaReplace(float alpha)
```

Skapar Alpha replace-effekt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alpha | float | Alpha |

**Returnerar:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Alpha replace-effekt.
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public final IBiLevel createBiLevel(float threshold)
```

Skapar BiLevel-effekt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threshold | float | Tröskel. |

**Returnerar:**
[IBiLevel](../../com.aspose.slides/ibilevel) - BiLevel-effekt.
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public final IBlur createBlur(double radius, boolean grow)
```

Skapar Blur-effekt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| radius | double | Radie. |
| grow | boolean | Väx. |

**Returnerar:**
[IBlur](../../com.aspose.slides/iblur) - Blur-effekt.
### createColorChange() {#createColorChange--}
```
public final IColorChange createColorChange()
```

Skapar Color change-effekt.

**Returnerar:**
[IColorChange](../../com.aspose.slides/icolorchange) - Color change-effekt.
### createColorReplace() {#createColorReplace--}
```
public final IColorReplace createColorReplace()
```

Skapar Color replace-effekt.

**Returnerar:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Color replace-effekt.
### createDuotone() {#createDuotone--}
```
public final IDuotone createDuotone()
```

Skapar Duotone-effekt.

**Returnerar:**
[IDuotone](../../com.aspose.slides/iduotone) - Duotone-effekt.
### createFillOverlay() {#createFillOverlay--}
```
public final IFillOverlay createFillOverlay()
```

Skapar Fill overlay-effekt.

**Returnerar:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Fill overlay-effekt.
### createGrayScale() {#createGrayScale--}
```
public final IGrayScale createGrayScale()
```

Skapar Gray scale-effekt.

**Returnerar:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Gray scale-effekt.
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public final IHSL createHSL(float hue, float saturation, float luminance)
```

Skapar Hue Saturation Luminance-effekt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hue | float | Nyans. |
| saturation | float | Mättnad. |
| luminance | float | Luminans. |

**Returnerar:**
[IHSL](../../com.aspose.slides/ihsl) - HSL-effekt.
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public final ILuminance createLuminance(float brightness, float contrast)
```

Skapar Luminance-effekt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brightness | float | Ljusstyrka. |
| contrast | float | Kontrast. |

**Returnerar:**
[ILuminance](../../com.aspose.slides/iluminance) - Luminance-effekt.
### createTint(float hue, float amount) {#createTint-float-float-}
```
public final ITint createTint(float hue, float amount)
```

Skapar Tint-effekt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hue | float | Nyans. |
| amount | float | Mängd. |

**Returnerar:**
[ITint](../../com.aspose.slides/itint) - Tint-effekt.
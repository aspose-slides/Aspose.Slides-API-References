---
title: ImageTransformOperationFactory
second_title: Aspose.Slides für Android über Java API-Referenz
description: Ermöglicht das Erstellen von Bildtransformationsoperationen
type: docs
url: /de/com.aspose.slides/imagetransformoperationfactory/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory)
```
public class ImageTransformOperationFactory implements IImageTransformOperationFactory
```

Ermöglicht das Erstellen von Bildtransformationsoperationen

--------------------

Für COM-Kompatibilität.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ImageTransformOperationFactory()](#ImageTransformOperationFactory--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | Erstellt Alpha BiLevel Effekt. |
| [createAlphCeiling()](#createAlphCeiling--) | Erstellt Alpha Ceiling Effekt. |
| [createAlphaFloor()](#createAlphaFloor--) | Erstellt Alpha floor Effekt. |
| [createAlphaInverse()](#createAlphaInverse--) | Erstellt Alpha inverse Effekt. |
| [createAlphaModulate()](#createAlphaModulate--) | Erstellt Alpha modulate Effekt. |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | Erstellt Alpha modulate fixed Effekt. |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | Erstellt Alpha replace Effekt. |
| [createBiLevel(float threshold)](#createBiLevel-float-) | Erstellt BiLevel Effekt. |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | Erstellt Blur Effekt. |
| [createColorChange()](#createColorChange--) | Erstellt Color change Effekt. |
| [createColorReplace()](#createColorReplace--) | Erstellt Color replace Effekt. |
| [createDuotone()](#createDuotone--) | Erstellt Duotone Effekt. |
| [createFillOverlay()](#createFillOverlay--) | Erstellt Fill overlay Effekt. |
| [createGrayScale()](#createGrayScale--) | Erstellt Gray scale Effekt. |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | Erstellt Hue Saturation Luminance Effekt. |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | Erstellt Luminance Effekt. |
| [createTint(float hue, float amount)](#createTint-float-float-) | Erstellt Tint Effekt. |

### ImageTransformOperationFactory() {#ImageTransformOperationFactory--}
```
public ImageTransformOperationFactory()
```

### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public final IAlphaBiLevel createAlphaBiLevel(float threshold)
```

Erstellt Alpha BiLevel Effekt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threshold | float | Schwellenwert. |

**Rückgabewert:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Alpha BiLevel Effekt.

### createAlphCeiling() {#createAlphCeiling--}
```
public final IAlphaCeiling createAlphCeiling()
```

Erstellt Alpha Ceiling Effekt.

**Rückgabewert:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Alpha Ceiling Effekt.

### createAlphaFloor() {#createAlphaFloor--}
```
public final IAlphaFloor createAlphaFloor()
```

Erstellt Alpha floor Effekt.

**Rückgabewert:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Alpha floor Effekt.

### createAlphaInverse() {#createAlphaInverse--}
```
public final IAlphaInverse createAlphaInverse()
```

Erstellt Alpha inverse Effekt.

**Rückgabewert:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Alpha inverst Effekt.

### createAlphaModulate() {#createAlphaModulate--}
```
public final IAlphaModulate createAlphaModulate()
```

Erstellt Alpha modulate Effekt.

**Rückgabewert:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Alpha modulate Effekt.

### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public final IAlphaModulateFixed createAlphaModulateFixed(float amount)
```

Erstellt Alpha modulate fixed Effekt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| amount | float | Betrag. |

**Rückgabewert:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Alpha modulate fixed Effekt.

### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public final IAlphaReplace createAlphaReplace(float alpha)
```

Erstellt Alpha replace Effekt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| alpha | float | Alpha |

**Rückgabewert:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Alpha replace Effekt.

### createBiLevel(float threshold) {#createBiLevel-float-}
```
public final IBiLevel createBiLevel(float threshold)
```

Erstellt BiLevel Effekt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threshold | float | Schwellenwert. |

**Rückgabewert:**
[IBiLevel](../../com.aspose.slides/ibilevel) - BiLevel Effekt.

### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public final IBlur createBlur(double radius, boolean grow)
```

Erstellt Blur Effekt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| radius | double | Radius. |
| grow | boolean | Vergrößern. |

**Rückgabewert:**
[IBlur](../../com.aspose.slides/iblur) - Blur Effekt.

### createColorChange() {#createColorChange--}
```
public final IColorChange createColorChange()
```

Erstellt Color change Effekt.

**Rückgabewert:**
[IColorChange](../../com.aspose.slides/icolorchange) - Color change Effekt.

### createColorReplace() {#createColorReplace--}
```
public final IColorReplace createColorReplace()
```

Erstellt Color replace Effekt.

**Rückgabewert:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Color replace Effekt.

### createDuotone() {#createDuotone--}
```
public final IDuotone createDuotone()
```

Erstellt Duotone Effekt.

**Rückgabewert:**
[IDuotone](../../com.aspose.slides/iduotone) - Duotone Effekt.

### createFillOverlay() {#createFillOverlay--}
```
public final IFillOverlay createFillOverlay()
```

Erstellt Fill overlay Effekt.

**Rückgabewert:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Fill overlay Effekt.

### createGrayScale() {#createGrayScale--}
```
public final IGrayScale createGrayScale()
```

Erstellt Gray scale Effekt.

**Rückgabewert:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Returns gray scale Effekt.

### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public final IHSL createHSL(float hue, float saturation, float luminance)
```

Erstellt Hue Saturation Luminance Effekt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hue | float | Farbton. |
| saturation | float | Sättigung. |
| luminance | float | Helligkeit. |

**Rückgabewert:**
[IHSL](../../com.aspose.slides/ihsl) - HSL Effekt.

### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public final ILuminance createLuminance(float brightness, float contrast)
```

Erstellt Luminance Effekt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brightness | float | Helligkeit. |
| contrast | float | Kontrast. |

**Rückgabewert:**
[ILuminance](../../com.aspose.slides/iluminance) - Luminance Effekt.

### createTint(float hue, float amount) {#createTint-float-float-}
```
public final ITint createTint(float hue, float amount)
```

Erstellt Tint Effekt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hue | float | Farbton. |
| amount | float | Betrag. |

**Rückgabewert:**
[ITint](../../com.aspose.slides/itint) - Tint Effekt.
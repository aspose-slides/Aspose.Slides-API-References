---
title: IImageTransformOperationFactory
second_title: Aspose.Slides für Android über Java API-Referenz
description: Ermöglicht das Erstellen von Bild-Effekt-Instanzen
type: docs
url: /de/com.aspose.slides/iimagetransformoperationfactory/
---```
public interface IImageTransformOperationFactory
```

Ermöglicht das Erstellen von Bild-Effekt-Instanzen

--------------------

Für COM-Schnittstelle.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | Erstellt Alpha BiLevel-Effekt. |
| [createAlphCeiling()](#createAlphCeiling--) | Erstellt Alpha Ceiling-Effekt. |
| [createAlphaFloor()](#createAlphaFloor--) | Erstellt Alpha floor-Effekt. |
| [createAlphaInverse()](#createAlphaInverse--) | Erstellt Alpha inverse-Effekt. |
| [createAlphaModulate()](#createAlphaModulate--) | Erstellt Alpha modulate-Effekt. |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | Erstellt Alpha modulate fixed-Effekt. |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | Erstellt Alpha replace-Effekt. |
| [createBiLevel(float threshold)](#createBiLevel-float-) | Erstellt BiLevel-Effekt. |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | Erstellt Blur-Effekt. |
| [createColorChange()](#createColorChange--) | Erstellt Color change-Effekt. |
| [createColorReplace()](#createColorReplace--) | Erstellt Color replace-Effekt. |
| [createDuotone()](#createDuotone--) | Erstellt Duotone-Effekt. |
| [createFillOverlay()](#createFillOverlay--) | Erstellt Fill overlay-Effekt. |
| [createGrayScale()](#createGrayScale--) | Erstellt Gray scale-Effekt. |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | Erstellt Hue Saturation Luminance-Effekt. |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | Erstellt Luminance-Effekt. |
| [createTint(float hue, float amount)](#createTint-float-float-) | Erstellt Tint-Effekt. |
### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public abstract IAlphaBiLevel createAlphaBiLevel(float threshold)
```

Erstellt Alpha BiLevel-Effekt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threshold | float | Schwellenwert. |

**Rückgabewert:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Alpha BiLevel-Effekt.
### createAlphCeiling() {#createAlphCeiling--}
```
public abstract IAlphaCeiling createAlphCeiling()
```

Erstellt Alpha Ceiling-Effekt.

**Rückgabewert:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Alpha Ceiling-Effekt.
### createAlphaFloor() {#createAlphaFloor--}
```
public abstract IAlphaFloor createAlphaFloor()
```

Erstellt Alpha floor-Effekt.

**Rückgabewert:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Alpha floor-Effekt.
### createAlphaInverse() {#createAlphaInverse--}
```
public abstract IAlphaInverse createAlphaInverse()
```

Erstellt Alpha inverse-Effekt.

**Rückgabewert:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Alpha inverse-Effekt.
### createAlphaModulate() {#createAlphaModulate--}
```
public abstract IAlphaModulate createAlphaModulate()
```

Erstellt Alpha modulate-Effekt.

**Rückgabewert:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Alpha modulate-Effekt.
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public abstract IAlphaModulateFixed createAlphaModulateFixed(float amount)
```

Erstellt Alpha modulate fixed-Effekt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| amount | float | Menge. |

**Rückgabewert:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Alpha modulate fixed-Effekt.
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public abstract IAlphaReplace createAlphaReplace(float alpha)
```

Erstellt Alpha replace-Effekt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| alpha | float | Alpha |
 
**Rückgabewert:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Alpha replace-Effekt.
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public abstract IBiLevel createBiLevel(float threshold)
```

Erstellt BiLevel-Effekt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threshold | float | Schwellenwert. |

**Rückgabewert:**
[IBiLevel](../../com.aspose.slides/ibilevel) - BiLevel-Effekt.
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public abstract IBlur createBlur(double radius, boolean grow)
```

Erstellt Blur-Effekt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| radius | double | Radius. |
| grow | boolean | Vergrößern. |

**Rückgabewert:**
[IBlur](../../com.aspose.slides/iblur) - Blur-Effekt.
### createColorChange() {#createColorChange--}
```
public abstract IColorChange createColorChange()
```

Erstellt Color change-Effekt.

**Rückgabewert:**
[IColorChange](../../com.aspose.slides/icolorchange) - Color change-Effekt.
### createColorReplace() {#createColorReplace--}
```
public abstract IColorReplace createColorReplace()
```

Erstellt Color replace-Effekt.

**Rückgabewert:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Color replace-Effekt.
### createDuotone() {#createDuotone--}
```
public abstract IDuotone createDuotone()
```

Erstellt Duotone-Effekt.

**Rückgabewert:**
[IDuotone](../../com.aspose.slides/iduotone) - Duotone-Effekt.
### createFillOverlay() {#createFillOverlay--}
```
public abstract IFillOverlay createFillOverlay()
```

Erstellt Fill overlay-Effekt.

**Rückgabewert:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Fill overlay-Effekt.
### createGrayScale() {#createGrayScale--}
```
public abstract IGrayScale createGrayScale()
```

Erstellt Gray scale-Effekt.

**Rückgabewert:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Gibt Gray scale-Effekt zurück.
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public abstract IHSL createHSL(float hue, float saturation, float luminance)
```

Erstellt Hue Saturation Luminance-Effekt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hue | float | Farbton. |
| saturation | float | Sättigung. |
| luminance | float | Luminanz. |

**Rückgabewert:**
[IHSL](../../com.aspose.slides/ihsl) - HSL-Effekt.
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public abstract ILuminance createLuminance(float brightness, float contrast)
```

Erstellt Luminance-Effekt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brightness | float | Helligkeit. |
| contrast | float | Kontrast. |

**Rückgabewert:**
[ILuminance](../../com.aspose.slides/iluminance) - Luminance-Effekt.
### createTint(float hue, float amount) {#createTint-float-float-}
```
public abstract ITint createTint(float hue, float amount)
```

Erstellt Tint-Effekt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hue | float | Farbton. |
| amount | float | Menge. |

**Rückgabewert:**
[ITint](../../com.aspose.slides/itint) - Tint-Effekt.
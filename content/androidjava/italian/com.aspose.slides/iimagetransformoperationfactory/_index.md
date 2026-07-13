---
title: IImageTransformOperationFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create image effects instances
type: docs
url: /it/com.aspose.slides/iimagetransformoperationfactory/
---```
public interface IImageTransformOperationFactory
```

Consente di creare istanze di effetti immagine

--------------------

Per l'interfaccia COM.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | Crea effetto Alpha BiLevel. |
| [createAlphCeiling()](#createAlphCeiling--) | Crea effetto Alpha Ceiling. |
| [createAlphaFloor()](#createAlphaFloor--) | Crea effetto Alpha floor. |
| [createAlphaInverse()](#createAlphaInverse--) | Crea effetto Alpha inverse. |
| [createAlphaModulate()](#createAlphaModulate--) | Crea effetto Alpha modulate. |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | Crea effetto Alpha modulate fixed. |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | Crea effetto Alpha replace. |
| [createBiLevel(float threshold)](#createBiLevel-float-) | Crea effetto BiLevel. |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | Crea effetto Blur. |
| [createColorChange()](#createColorChange--) | Crea effetto Color change. |
| [createColorReplace()](#createColorReplace--) | Crea effetto Color replace. |
| [createDuotone()](#createDuotone--) | Crea effetto Duotone. |
| [createFillOverlay()](#createFillOverlay--) | Crea effetto Fill overlay. |
| [createGrayScale()](#createGrayScale--) | Crea effetto Gray scale. |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | Crea effetto Hue Saturation Luminance. |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | Crea effetto Luminance. |
| [createTint(float hue, float amount)](#createTint-float-float-) | Crea effetto Tint. |
### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public abstract IAlphaBiLevel createAlphaBiLevel(float threshold)
```

Crea effetto Alpha BiLevel.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threshold | float | Soglia. |

**Restituisce:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - effetto Alpha BiLevel.
### createAlphCeiling() {#createAlphCeiling--}
```
public abstract IAlphaCeiling createAlphCeiling()
```

Crea effetto Alpha Ceiling.

**Restituisce:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - effetto Alpha Ceiling.
### createAlphaFloor() {#createAlphaFloor--}
```
public abstract IAlphaFloor createAlphaFloor()
```

Crea effetto Alpha floor.

**Restituisce:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - effetto Alpha floor.
### createAlphaInverse() {#createAlphaInverse--}
```
public abstract IAlphaInverse createAlphaInverse()
```

Crea effetto Alpha inverse.

**Restituisce:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - effetto Alpha inverse.
### createAlphaModulate() {#createAlphaModulate--}
```
public abstract IAlphaModulate createAlphaModulate()
```

Crea effetto Alpha modulate.

**Restituisce:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - effetto Alpha modulate.
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public abstract IAlphaModulateFixed createAlphaModulateFixed(float amount)
```

Crea effetto Alpha modulate fixed.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| amount | float | Quantità. |

**Restituisce:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - effetto Alpha modulate fixed.
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public abstract IAlphaReplace createAlphaReplace(float alpha)
```

Crea effetto Alpha replace.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| alpha | float | Alpha |

**Restituisce:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - effetto Alpha replace.
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public abstract IBiLevel createBiLevel(float threshold)
```

Crea effetto BiLevel.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threshold | float | Soglia. |

**Restituisce:**
[IBiLevel](../../com.aspose.slides/ibilevel) - effetto BiLevel.
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public abstract IBlur createBlur(double radius, boolean grow)
```

Crea effetto Blur.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| radius | double | Radius. |
| grow | boolean | Grow. |

**Restituisce:**
[IBlur](../../com.aspose.slides/iblur) - effetto Blur.
### createColorChange() {#createColorChange--}
```
public abstract IColorChange createColorChange()
```

Crea effetto Color change.

**Restituisce:**
[IColorChange](../../com.aspose.slides/icolorchange) - effetto Color change.
### createColorReplace() {#createColorReplace--}
```
public abstract IColorReplace createColorReplace()
```

Crea effetto Color replace.

**Restituisce:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - effetto Color replace.
### createDuotone() {#createDuotone--}
```
public abstract IDuotone createDuotone()
```

Crea effetto Duotone.

**Restituisce:**
[IDuotone](../../com.aspose.slides/iduotone) - effetto Duotone.
### createFillOverlay() {#createFillOverlay--}
```
public abstract IFillOverlay createFillOverlay()
```

Crea effetto Fill overlay.

**Restituisce:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - effetto Fill overlay.
### createGrayScale() {#createGrayScale--}
```
public abstract IGrayScale createGrayScale()
```

Crea effetto Gray scale.

**Restituisce:**
[IGrayScale](../../com.aspose.slides/igrayscale) - effetto Gray scale.
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public abstract IHSL createHSL(float hue, float saturation, float luminance)
```

Crea effetto Hue Saturation Luminance.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hue | float | Hue. |
| saturation | float | Saturation. |
| luminance | float | Luminance. |

**Restituisce:**
[IHSL](../../com.aspose.slides/ihsl) - effetto HSL.
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public abstract ILuminance createLuminance(float brightness, float contrast)
```

Crea effetto Luminance.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brightness | float | Brightness. |
| contrast | float | Contrast. |

**Restituisce:**
[ILuminance](../../com.aspose.slides/iluminance) - effetto Luminance.
### createTint(float hue, float amount) {#createTint-float-float-}
```
public abstract ITint createTint(float hue, float amount)
```

Crea effetto Tint.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hue | float | Hue. |
| amount | float | Quantità. |

**Restituisce:**
[ITint](../../com.aspose.slides/itint) - effetto Tint.
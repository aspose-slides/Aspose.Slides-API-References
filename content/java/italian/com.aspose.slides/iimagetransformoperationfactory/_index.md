---
title: IImageTransformOperationFactory
second_title: Aspose.Slides for Java API Reference
description: Consente di creare istanze di effetti immagine
type: docs
url: /it/com.aspose.slides/iimagetransformoperationfactory/
---```
public interface IImageTransformOperationFactory
```

Consente di creare istanze di effetti immagine

--------------------

Per interfaccia COM.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | Crea l'effetto Alpha BiLevel. |
| [createAlphCeiling()](#createAlphCeiling--) | Crea l'effetto Alpha Ceiling. |
| [createAlphaFloor()](#createAlphaFloor--) | Crea l'effetto Alpha floor. |
| [createAlphaInverse()](#createAlphaInverse--) | Crea l'effetto Alpha inverse. |
| [createAlphaModulate()](#createAlphaModulate--) | Crea l'effetto Alpha modulate. |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | Crea l'effetto Alpha modulate fixed. |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | Crea l'effetto Alpha replace. |
| [createBiLevel(float threshold)](#createBiLevel-float-) | Crea l'effetto BiLevel. |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | Crea l'effetto Blur. |
| [createColorChange()](#createColorChange--) | Crea l'effetto Color change. |
| [createColorReplace()](#createColorReplace--) | Crea l'effetto Color replace. |
| [createDuotone()](#createDuotone--) | Crea l'effetto Duotone. |
| [createFillOverlay()](#createFillOverlay--) | Crea l'effetto Fill overlay. |
| [createGrayScale()](#createGrayScale--) | Crea l'effetto Gray scale. |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | Crea l'effetto Hue Saturation Luminance. |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | Crea l'effetto Luminance. |
| [createTint(float hue, float amount)](#createTint-float-float-) | Crea l'effetto Tint. |
### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public abstract IAlphaBiLevel createAlphaBiLevel(float threshold)
```

Crea l'effetto Alpha BiLevel.

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

Crea l'effetto Alpha Ceiling.

**Restituisce:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - effetto Alpha Ceiling.
### createAlphaFloor() {#createAlphaFloor--}
```
public abstract IAlphaFloor createAlphaFloor()
```

Crea l'effetto Alpha floor.

**Restituisce:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - effetto Alpha floor.
### createAlphaInverse() {#createAlphaInverse--}
```
public abstract IAlphaInverse createAlphaInverse()
```

Crea l'effetto Alpha inverse.

**Restituisce:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - effetto Alpha inverse.
### createAlphaModulate() {#createAlphaModulate--}
```
public abstract IAlphaModulate createAlphaModulate()
```

Crea l'effetto Alpha modulate.

**Restituisce:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - effetto Alpha modulate.
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public abstract IAlphaModulateFixed createAlphaModulateFixed(float amount)
```

Crea l'effetto Alpha modulate fixed.

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

Crea l'effetto Alpha replace.

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

Crea l'effetto BiLevel.

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

Crea l'effetto Blur.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| radius | double | Raggio. |
| grow | boolean | Crescita. |

**Restituisce:**
[IBlur](../../com.aspose.slides/iblur) - effetto Blur.
### createColorChange() {#createColorChange--}
```
public abstract IColorChange createColorChange()
```

Crea l'effetto Color change.

**Restituisce:**
[IColorChange](../../com.aspose.slides/icolorchange) - effetto Color change.
### createColorReplace() {#createColorReplace--}
```
public abstract IColorReplace createColorReplace()
```

Crea l'effetto Color replace.

**Restituisce:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - effetto Color replace.
### createDuotone() {#createDuotone--}
```
public abstract IDuotone createDuotone()
```

Crea l'effetto Duotone.

**Restituisce:**
[IDuotone](../../com.aspose.slides/iduotone) - effetto Duotone.
### createFillOverlay() {#createFillOverlay--}
```
public abstract IFillOverlay createFillOverlay()
```

Crea l'effetto Fill overlay.

**Restituisce:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - effetto Fill overlay.
### createGrayScale() {#createGrayScale--}
```
public abstract IGrayScale createGrayScale()
```

Crea l'effetto Gray scale.

**Restituisce:**
[IGrayScale](../../com.aspose.slides/igrayscale) - effetto Gray scale.
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public abstract IHSL createHSL(float hue, float saturation, float luminance)
```

Crea l'effetto Hue Saturation Luminance.

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

Crea l'effetto Luminance.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brightness | float | Luminosità. |
| contrast | float | Contrasto. |

**Restituisce:**
[ILuminance](../../com.aspose.slides/iluminance) - effetto Luminance.
### createTint(float hue, float amount) {#createTint-float-float-}
```
public abstract ITint createTint(float hue, float amount)
```

Crea l'effetto Tint.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hue | float | Hue. |
| amount | float | Quantità. |

**Restituisce:**
[ITint](../../com.aspose.slides/itint) - effetto Tint.
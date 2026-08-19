---
title: ImageTransformOperationFactory
second_title: Riferimento API di Aspose.Slides per Java
description: Consente di creare operazioni di trasformazione dell'immagine
type: docs
url: /it/com.aspose.slides/imagetransformoperationfactory/
---
**Inheritance:**  
java.lang.Object  

**All Implemented Interfaces:**  
[com.aspose.slides.IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory)  
```
public class ImageTransformOperationFactory implements IImageTransformOperationFactory
```

Consente di creare operazioni di trasformazione dell'immagine

--------------------

Per compatibilità COM.  
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ImageTransformOperationFactory()](#ImageTransformOperationFactory--) |  |
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
### ImageTransformOperationFactory() {#ImageTransformOperationFactory--}
```
public ImageTransformOperationFactory()
```

### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public final IAlphaBiLevel createAlphaBiLevel(float threshold)
```

Crea l'effetto Alpha BiLevel.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threshold | float | Soglia. |

**Restituisce:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Alpha BiLevel effect.
### createAlphCeiling() {#createAlphCeiling--}
```
public final IAlphaCeiling createAlphCeiling()
```

Crea l'effetto Alpha Ceiling.

**Restituisce:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Alpha Ceiling effect.
### createAlphaFloor() {#createAlphaFloor--}
```
public final IAlphaFloor createAlphaFloor()
```

Crea l'effetto Alpha floor.

**Restituisce:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Alpha floor effect.
### createAlphaInverse() {#createAlphaInverse--}
```
public final IAlphaInverse createAlphaInverse()
```

Crea l'effetto Alpha inverse.

**Restituisce:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Alpha inverst effect.
### createAlphaModulate() {#createAlphaModulate--}
```
public final IAlphaModulate createAlphaModulate()
```

Crea l'effetto Alpha modulate.

**Restituisce:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Alpha modulate effect.
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public final IAlphaModulateFixed createAlphaModulateFixed(float amount)
```

Crea l'effetto Alpha modulate fixed.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| amount | float | Quantità. |

**Restituisce:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Alpha modulate fixed effect.
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public final IAlphaReplace createAlphaReplace(float alpha)
```

Crea l'effetto Alpha replace.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| alpha | float | Alpha |

**Restituisce:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Alpha replace effect.
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public final IBiLevel createBiLevel(float threshold)
```

Crea l'effetto BiLevel.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threshold | float | Soglia. |

**Restituisce:**
[IBiLevel](../../com.aspose.slides/ibilevel) - BiLevel effect.
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public final IBlur createBlur(double radius, boolean grow)
```

Crea l'effetto Blur.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| radius | double | Raggio. |
| grow | boolean | Crescita. |

**Restituisce:**
[IBlur](../../com.aspose.slides/iblur) - Blur effect.
### createColorChange() {#createColorChange--}
```
public final IColorChange createColorChange()
```

Crea l'effetto Color change.

**Restituisce:**
[IColorChange](../../com.aspose.slides/icolorchange) - Color change effect.
### createColorReplace() {#createColorReplace--}
```
public final IColorReplace createColorReplace()
```

Crea l'effetto Color replace.

**Restituisce:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Color replace effect.
### createDuotone() {#createDuotone--}
```
public final IDuotone createDuotone()
```

Crea l'effetto Duotone.

**Restituisce:**
[IDuotone](../../com.aspose.slides/iduotone) - Duotone effect.
### createFillOverlay() {#createFillOverlay--}
```
public final IFillOverlay createFillOverlay()
```

Crea l'effetto Fill overlay.

**Restituisce:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Fill overlay effect.
### createGrayScale() {#createGrayScale--}
```
public final IGrayScale createGrayScale()
```

Crea l'effetto Gray scale.

**Restituisce:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Restituisce gray scale effect.
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public final IHSL createHSL(float hue, float saturation, float luminance)
```

Crea l'effetto Hue Saturation Luminance.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hue | float | Tonalità. |
| saturation | float | Saturazione. |
| luminance | float | Luminanza. |

**Restituisce:**
[IHSL](../../com.aspose.slides/ihsl) - HSL effect.
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public final ILuminance createLuminance(float brightness, float contrast)
```

Crea l'effetto Luminance.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brightness | float | Luminosità. |
| contrast | float | Contrasto. |

**Restituisce:**
[ILuminance](../../com.aspose.slides/iluminance) - Luminance effect.
### createTint(float hue, float amount) {#createTint-float-float-}
```
public final ITint createTint(float hue, float amount)
```

Crea l'effetto Tint.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hue | float | Tonalità. |
| amount | float | Quantità. |

**Restituisce:**
[ITint](../../com.aspose.slides/itint) - Tint effect.
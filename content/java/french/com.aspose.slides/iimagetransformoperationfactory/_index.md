---
title: IImageTransformOperationFactory
second_title: Aspose.Slides for Java API Reference
description: Permet de créer des instances d'effets d'image
type: docs
url: /fr/com.aspose.slides/iimagetransformoperationfactory/
---```
public interface IImageTransformOperationFactory
```

Permet de créer des instances d'effets d'image

--------------------

Pour l'interface COM.
## Méthodes

| Méthode | Description |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | Creates Alpha BiLevel effect. |
| [createAlphCeiling()](#createAlphCeiling--) | Creates Alpha Ceiling effect. |
| [createAlphaFloor()](#createAlphaFloor--) | Creates Alpha floor effect. |
| [createAlphaInverse()](#createAlphaInverse--) | Creates Alpha inverse effect. |
| [createAlphaModulate()](#createAlphaModulate--) | Creates Alpha modulate effect. |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | Creates Alpha modulate fixed effect. |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | Creates Alpha replace effect. |
| [createBiLevel(float threshold)](#createBiLevel-float-) | Creates BiLevel effect. |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | Creates Blur effect. |
| [createColorChange()](#createColorChange--) | Creates Color change effect. |
| [createColorReplace()](#createColorReplace--) | Creates Color replace effect. |
| [createDuotone()](#createDuotone--) | Creates Duotone effect. |
| [createFillOverlay()](#createFillOverlay--) | Creates Fill overlay effect. |
| [createGrayScale()](#createGrayScale--) | Creates Gray scale effect. |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | Creates Hue Saturation Luminance effect. |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | Createtes Luminance effect. |
| [createTint(float hue, float amount)](#createTint-float-float-) | Creates Tint effect. |
### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public abstract IAlphaBiLevel createAlphaBiLevel(float threshold)
```

Crée l'effet Alpha BiLevel.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| threshold | float | Threshold. |

**Renvoie :**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Alpha BiLevel effet.

### createAlphCeiling() {#createAlphCeiling--}
```
public abstract IAlphaCeiling createAlphCeiling()
```

Crée l'effet Alpha Ceiling.

**Renvoie :**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Alpha Ceiling effet.

### createAlphaFloor() {#createAlphaFloor--}
```
public abstract IAlphaFloor createAlphaFloor()
```

Crée l'effet Alpha floor.

**Renvoie :**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Alpha floor effet.

### createAlphaInverse() {#createAlphaInverse--}
```
public abstract IAlphaInverse createAlphaInverse()
```

Crée l'effet Alpha inverse.

**Renvoie :**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Alpha inverse effet.

### createAlphaModulate() {#createAlphaModulate--}
```
public abstract IAlphaModulate createAlphaModulate()
```

Crée l'effet Alpha modulate.

**Renvoie :**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Alpha modulate effet.

### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public abstract IAlphaModulateFixed createAlphaModulateFixed(float amount)
```

Crée l'effet Alpha modulate fixed.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| amount | float | Amount. |

**Renvoie :**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Alpha modulate fixed effet.

### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public abstract IAlphaReplace createAlphaReplace(float alpha)
```

Crée l'effet Alpha replace.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| alpha | float | Alpha |

**Renvoie :**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Alpha replace effet.

### createBiLevel(float threshold) {#createBiLevel-float-}
```
public abstract IBiLevel createBiLevel(float threshold)
```

Crée l'effet BiLevel.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| threshold | float | Threshold. |

**Renvoie :**
[IBiLevel](../../com.aspose.slides/ibilevel) - BiLevel effet.

### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public abstract IBlur createBlur(double radius, boolean grow)
```

Crée l'effet Blur.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| radius | double | Radius. |
| grow | boolean | Grow. |

**Renvoie :**
[IBlur](../../com.aspose.slides/iblur) - Blur effet.

### createColorChange() {#createColorChange--}
```
public abstract IColorChange createColorChange()
```

Crée l'effet Color change.

**Renvoie :**
[IColorChange](../../com.aspose.slides/icolorchange) - Color change effet.

### createColorReplace() {#createColorReplace--}
```
public abstract IColorReplace createColorReplace()
```

Crée l'effet Color replace.

**Renvoie :**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Color replace effet.

### createDuotone() {#createDuotone--}
```
public abstract IDuotone createDuotone()
```

Crée l'effet Duotone.

**Renvoie :**
[IDuotone](../../com.aspose.slides/iduotone) - Duotone effet.

### createFillOverlay() {#createFillOverlay--}
```
public abstract IFillOverlay createFillOverlay()
```

Crée l'effet Fill overlay.

**Renvoie :**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Fill overlay effet.

### createGrayScale() {#createGrayScale--}
```
public abstract IGrayScale createGrayScale()
```

Crée l'effet Gray scale.

**Renvoie :**
[IGrayScale](../../com.aspose.slides/igrayscale) - Returns gray scale effet.

### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public abstract IHSL createHSL(float hue, float saturation, float luminance)
```

Crée l'effet Hue Saturation Luminance.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| hue | float | Hue. |
| saturation | float | Saturation. |
| luminance | float | Luminance. |

**Renvoie :**
[IHSL](../../com.aspose.slides/ihsl) - HSL effet.

### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public abstract ILuminance createLuminance(float brightness, float contrast)
```

Crée l'effet Luminance.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| brightness | float | Brightness. |
| contrast | float | Contrast. |

**Renvoie :**
[ILuminance](../../com.aspose.slides/iluminance) - Luminance effet.

### createTint(float hue, float amount) {#createTint-float-float-}
```
public abstract ITint createTint(float hue, float amount)
```

Crée l'effet Tint.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| hue | float | Hue. |
| amount | float | Amount. |

**Renvoie :**
[ITint](../../com.aspose.slides/itint) - Tint effet.
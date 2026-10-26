---
title: IImageTransformOperationFactory
second_title: Aspose.Slides pour Android via la référence API Java
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
| threshold | float | Seuil. |

**Retour :**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - effet Alpha BiLevel.

### createAlphCeiling() {#createAlphCeiling--}
```
public abstract IAlphaCeiling createAlphCeiling()
```

Crée l'effet Alpha Ceiling.

**Retour :**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - effet Alpha Ceiling.

### createAlphaFloor() {#createAlphaFloor--}
```
public abstract IAlphaFloor createAlphaFloor()
```

Crée l'effet Alpha floor.

**Retour :**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - effet Alpha floor.

### createAlphaInverse() {#createAlphaInverse--}
```
public abstract IAlphaInverse createAlphaInverse()
```

Crée l'effet Alpha inverse.

**Retour :**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - effet Alpha inverst.

### createAlphaModulate() {#createAlphaModulate--}
```
public abstract IAlphaModulate createAlphaModulate()
```

Crée l'effet Alpha modulate.

**Retour :**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - effet Alpha modulate.

### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public abstract IAlphaModulateFixed createAlphaModulateFixed(float amount)
```

Crée l'effet Alpha modulate fixed.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| amount | float | Amount. |

**Retour :**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - effet Alpha modulate fixed.

### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public abstract IAlphaReplace createAlphaReplace(float alpha)
```

Crée l'effet Alpha replace.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| alpha | float | Alpha |

**Retour :**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - effet Alpha replace.

### createBiLevel(float threshold) {#createBiLevel-float-}
```
public abstract IBiLevel createBiLevel(float threshold)
```

Crée l'effet BiLevel.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| threshold | float | Seuil. |

**Retour :**
[IBiLevel](../../com.aspose.slides/ibilevel) - effet BiLevel.

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

**Retour :**
[IBlur](../../com.aspose.slides/iblur) - effet Blur.

### createColorChange() {#createColorChange--}
```
public abstract IColorChange createColorChange()
```

Crée l'effet Color change.

**Retour :**
[IColorChange](../../com.aspose.slides/icolorchange) - effet Color change.

### createColorReplace() {#createColorReplace--}
```
public abstract IColorReplace createColorReplace()
```

Crée l'effet Color replace.

**Retour :**
[IColorReplace](../../com.aspose.slides/icolorreplace) - effet Color replace.

### createDuotone() {#createDuotone--}
```
public abstract IDuotone createDuotone()
```

Crée l'effet Duotone.

**Retour :**
[IDuotone](../../com.aspose.slides/iduotone) - effet Duotone.

### createFillOverlay() {#createFillOverlay--}
```
public abstract IFillOverlay createFillOverlay()
```

Crée l'effet Fill overlay.

**Retour :**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - effet Fill overlay.

### createGrayScale() {#createGrayScale--}
```
public abstract IGrayScale createGrayScale()
```

Crée l'effet Gray scale.

**Retour :**
[IGrayScale](../../com.aspose.slides/igrayscale) - Renvoie l'effet Gray scale.

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

**Retour :**
[IHSL](../../com.aspose.slides/ihsl) - effet HSL.

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

**Retour :**
[ILuminance](../../com.aspose.slides/iluminance) - effet Luminance.

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

**Retour :**
[ITint](../../com.aspose.slides/itint) - effet Tint.